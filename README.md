# Τίτλος εργασίας: Οπτικοποίηση δεδομένων χορηγιών (UK)

### Ονοματεπώνυμο: Τουλάκης Αλέξανδρος
### Αριθμός Μητρώου: Π2015067

* [Εκτελέσιμο παράδειγμα](https://p15githubstudent.github.io/D3js-uk-political-donations/ 'Εκτελέσιμο παράδειγμα')
* [Αποθετήριο κώδικα](https://github.com/P15GitHubStudent/D3js-uk-political-donations/tree/gh-pages ' Αποθετήριο κώδικα')

## Εισαγωγή
 Στα πλαίσια του μαθήματος Τεχνολογίες Λογισμικού του ΣΤ εξαμήνου επέλεξα την εργασία Data Visualization δεδομένων χορηγιών.

## Σύνοψη
Υλοποίησα τα ζητούμενα και των δύο παραδοτέων. Παρόλλα αυτά έκανα και κάποιες μπόνους προσθήκες  οπώς η δημιουργία ενός Bar Chart.  Όσο αφορά την δυναμική δημιουργία εικόνων η λειτουργεία  δουλεύει και στο Circle Pack Chart(άμα ο χρήστης  ακουμπήσει πάνω σε κύκλο του. Ακόμα στο ιστορικό που αποθηκεύονται οι εικόνες ο χρήστης έχει την δυνατότητα  να μπορεί να μεταβεί  μπροστά η πίσω στις σελίδες του ιστορικού. Για την δημιουργία μιας καινούργιας οπτικοποίσης από ανοικτά δεδομένα από επίσημη στατιστική αρχή έγινε δημιουργία τεσσάρων ομαδοποιήσεων καθώς και προσθήκη εικόνων για το tooltip πρόβλημα που αντιμετώπισα εδώ είναι οτι το github δεν με επέτρεψε να ανεβάσω και τις τριακόσιες εικόνες που ήθελα.

## Διαδικασία Ανάπτυξης
 Για την συγγραφή και την εκτέλεση του κώδικα έγινε χρήση ενός τοπικού ide(Sublime text )αντί της διαδικτυακής  πλατφόρμας του github. Στην συνέχεια , για  κάθε παραδοτέο κατέγραψα το τί πρέπει να κάνω, πώς το κάνω και τι προβλήματα μπορεί να αντιμετωπίσω στο μέλλον. Μετά έγινε προσπάθεια  υλοποίησης του κώδικα . Όσο αφορά το προγραμματιστικό κομμάτι πολλές φορές αντιμετώπισα προβλήματα λογικής και συντακτικής φύσεως για την αντιμετώπιση τους προέβη στις ακόλουθες ενέργειες. Αρχικά προσπαθούσα να δω που έγινε το λάθος στις περιπτώσεις που δεν κατάφερα να βγάλω  άκρη μόνος. Έψαξα να βρω πώς έλυσαν το ίδιο η παρόμοιο πρόβλημα άλλοι προγραμματιστές. Χρήσιμες ιστοσελίδες για να μάθω περισσότερα για την d3 και για debugging αποτέλεσαν.
1.	https://www.google.com/
2.	https://stackoverflow.com/
3.	https://github.com/d3/d3/wiki/Gallery
4.	https://developer.mozilla.org/el/

## Ανάλυση σχετικών έργων και εργαλείων
* Λογισμικό για την συγγραφή του κώδικα: [Sublime Text](https://www.sublimetext.com// 'Sublime Text')
* Λογισμικό επεξεργασίας εικόνων: [Paint.Net](https://www.getpaint.net/ 'Paint.Net')
* Framework [D3](https://d3js.org/ 'D3') για τις οπτικοποίσεις
* [Anime.js](http://animejs.com/ 'Anime.js') για το κινούμενο κείμενο

η εργασία βασίστηκε στον [κώδικα](https://github.com/ioniodi/D3js-uk-political-donations 'Κώδικα')


Αναλυτικές αλλαγές:
*	Δημιουργία καινούργιας ομαδοποίησης με τίτλο Group By The Amount Of Donation
*	Δημιουργία τρίων κουμπιών για να μπορεί να μεταβεί ο χρήστης στο Bubble, Circle Pack και Bar Chart αντίστοιχα(βρίσκονται στην ίδια σελίδα και όχι σε διαφορετική)
*	Δυνατότητα για zoom πάνω σε κείμενο χρήση του ποντικιού ως μεγεθυντικός φακός.
*	Προσθήκη ήχου κάθε φορά που ο χρήστης κάνει κλίκ πάνω σε ένα κουμπί

*	Δημιουργία κουμπιού Another Visualization έτσι ώστε ο χρήστης να μπορεί να μεταβεί στην καινούργια σελίδα με τις οπτικοποίησεις   με τα καινούργια στατιστικά δεδομένα
*	Όταν ο χρήστης πατήσει πάνω σε κύκλο με το ποντίκι τότε ανοίγει την μηχανή αναζήτης της google και ψάχνει το όνομα του δωρητή.
*	Όταν ο χρήστης αλλελιπιδράσει πάνω σε κύκλο τότε ακούγεται το ονομα και το ποσό της δωρεάς.
*	Δημιουργία των δύο ακόμα Προ αναφερόντων διαγραμμάτων οπτικοποιησής δεδομένων. 
*	Προσθήκη ιστορικού με εικόνες που προστείθενται δυναμικά όταν ο χρήστης πατήσει πάνω σε κύκλους.

## Ιστορικό 
Σε περίπτωση που ο χρήστης ακουμπήσει έναν κύκλο όταν βρίσκεται στο Bubble, CirclePack Chart  τότε δημιουργείται δυναμικά η εικόνα του δωρητή  και τοποθετείται στο ιστορικό. Αξίζει να σημειωθεί ότι οι εικόνες προστίθενται  με την δομή FIFO(First In First Out) .Το ιστορικό εκτός από τις  εικόνες έχει βελάκια για την μετακίνηση πίσω και μπροστά. Ο μέγιστος αριθμός που χωράει είναι σαράντα πέντε και σε κάθε σελίδα μπορεί να υπάρχουν μέχρι και εννέα εικόνες  . Ακόμα κάθε φορά που γίνεται αλληλεπίδραση με την εικόνα του ιστορικού τότε  εμφανίζεται το tooltip του donor . Άμα ο χρήστης πατήσει πάνω στην εικόνα τότε θα ανοίξει με καρτέλα στον browser και θα ψάξει το όνομα του δωρητή στην μηχανή αναζήτησης της Google.  Υπάρχει ενημερωτικό κείμενο στο ποια σελίδα του ιστορικού βρίσκεται ο χρήστης. Τέλος ο χρήστης έχει  επιλογή να διαγράψει όλα τα αντικείμενα του ιστορικού με το πάτημα πάνω στην επιλογή Clear History.

## Καινούργιο Γράφημα Οπτικοποίησης

## CirclePack 
Δήμιουργησα το CirclePack διάγραμμα για την οπτικοποίηση των ίδιων δεδομένων  είναι ενα διάγραμμα που επιτρέπτει την αναπαράσταση πολλών δεδομένων επίσης  συνδέεται και με την ιδεά της ομαδοποίησης όπου έχουμε κύκλους μέσα σε άλλλους κύκλους. Η επιπρόσθετη λειτουργικότητα  είναι η ίδια με αυτή του BubbleChart.

## BarChart
 εμφανίζει τις συχνότητες εμφάνισης των αποτελεσμάτων για κάθε  περιοχή της ομαδοποίησης η πληροφορία δεν παρέχεται από κανένα άλλο Chart που δημιουργήθηκε και θεωρήθηκε χρήσιμή η προσθήκη του.

## Δημιουργία του ίδιου D3 γραφήματος
Δήμιουργησα μια οπτικοποίηση (Bubble Chart) με καινούργια δεδομένα που βρήκα απο από την Euro Stat με θέμα [“Child and youth population on 1 January by sex and age”](http://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=yth_demo_010&lang=en '“Child and youth population on 1 January by sex and age”')

Από τα δεδομένα αυτά επέλεξα την ημερομηνία, την χώρα καθώς και το πληθυσμό των νέων και των παιδιών. Στην καινούργια οπτικοποίηση  δημιουργήθηκαν τέσσερίς  ομαδοποιήσεις. Η πρώτη αφορά διαχωρισμό με βάση τον πληθυσμό σε μικρό(  μικρότερο η ίσο με εφτακόσιες χιλιάδες ), μεσαίο(μικρότερο η ίσο με ένα εκατομμύριο ) και μεγάλο. Ο δεύτερος διαχωρισμός έγινε με βάση την ημερομηνία. Οι ημερομηνίες που επέλεξα είναι το 2015-2017.
Ο τρίτος διαχωρισμός έγινε με βάση το ageGroup (δηλαδή στην μία πλευρά τοποθετήθηκαν οι κύκλοι με τα παιδία ενώ στα άλλα με τους νέους.  Η ομαδοποίηση all απλά τοποθετεί όλους τους κύκλους μαζί . Ίσως αξίζει να αναφερθεί ότι η κόκκινοι κύκλοι είναι για το 2015 πράσινο για το 2016 και 2017  με μπλε, ακόμα άμα ο χρήστης αλλεπιδράσει πάνω σε έναν κύκλο εμφανίζεται το tooltip με στοιχεία το ageGroup, time, όνομα της χώρας και η εικόνα της. Ακόμα προστέθηκε κουμπί για να μπορούμε να μεταβούμε πίσω στην αρχική προσομοίωση. Τέλος όσο πιο μεγάλο είναι το μέγεθος των κύκλων τόσο πιο μεγάλο πληθυσμό αναπαριστούν .

# Αλλαγές στο κοινό αποθετήριο
Αρχικά δέσμευσα στο [issue1](https://github.com/ioniodi/D3js-uk-political-donations/issues/16 'issue1')
Ανέλαβα να βρω πέντε εικόνες για τους εξείς  δωρητές:
* Watford Business Club
* BECTU
* BFAWU
* Ethical Medicines Industry Group
* European Conservatives and Reformists

* Δημιούργησα επίσης το κατάλληλο csv με ονομα τον αριθμό μητρώου μου και πρόσθεσα το Ονομα, Επίθερο, Εξάμηνο και έθεσα τις τιμές Dileverable1 και 2 με την τιμή true εφόσον τελίωσα και τα δύο παραδοτέα.

Στον φάκελο participants τροποποίησα κατάλληλα το αρχείο index.html προκειμένου να εμφανίζονται η εικόνα του προφίλ και το ονομά μου με μια κίνηση η οποία έγινε με την χρήση της [Anime.js](http://animejs.com/ 'Anime.js'), Πρώτου όμως το κάνω αυτό πρώτα δέσμευσα την δεύτερη θέση στο [issue2](https://github.com/ioniodi/D3js-uk-political-donations/issues/16 'issue2').

Στην συνέχεια δημιούργησα ιστοσελίδα με τίτλο και όνομα κατάληξης html τον αριθμό  Μητρώου μου  η οποία χρησιμοποιεί το api του github προκειμένου να παίρνει δυναμικά στοιχεία των ονομάτων τις συνεισφορές που έχουν κάνει καθώς και το URL για το προφίλ έτσι όταν ο χρήστης κάνει κλικ πάνω στην περιοχή κάποιου τότε ανοίγει η σελίδα του προφίλ σε αυτόν που πάτησε πάνω.

Pull Request πρώτου παραδοτέου που έγινε αποδεκτό:https://github.com/ioniodi/D3js-uk-political-donations/pull/40


Pull Request Δεύτερου παραδοτέου που έγινε αποδεκτό:https://github.com/ioniodi/D3js-uk-political-donations/pull/271

## Ενδεικτικές οθόνες και animated gif

# Για Bubble Chart

* Αλλαγή χρωμάτων στις μπάλες με τα δεδομένα, καθώς και στα αντίστοιχα 3 πεδία της ομαδοποίησης Split by party.



![default](https://user-images.githubusercontent.com/22703561/36978016-d0188d94-208b-11e8-8781-5d541fa0ae46.PNG)



* google Search donor 



![googlesearch](https://user-images.githubusercontent.com/22703561/36980536-3c575d08-2093-11e8-8d9a-5ac0b87a8b5a.gif)



* Μεγένθυση όταν ο δείκτης βρίσκεται πάνω από τις λέξεις του κειμένου.



![zoom](https://user-images.githubusercontent.com/22703561/36979657-d5f234e0-2090-11e8-81f9-345f08321da7.gif)



* Νέο κουμπί για νέα ομαδοποίηση δεδομένων καθώς και την υλοποίηση της λειτουργείας αυτής: Split by amount of donation.



![komadopoisi](https://user-images.githubusercontent.com/22703561/36981125-fb68eb0c-2094-11e8-80bb-5632dd4a9ab5.PNG)

# Παραδοτέο 2 

* ιστορικό

![imghist](https://user-images.githubusercontent.com/22703561/39803549-f9622a22-5379-11e8-8b8c-74d9b42e4f6e.gif)

* CirclePack Chart


![circlepack](https://user-images.githubusercontent.com/22703561/39813027-85968bc4-5397-11e8-992d-988bbc3871d6.gif)


* Bar Chart
 ![barchart](https://user-images.githubusercontent.com/22703561/39803551-f9a9c008-5379-11e8-8f5d-4347d5ff8997.gif)


## Αλλαγές στο κοινό αποθετήριο

* κινούμενο κείμενο 


![animtext](https://user-images.githubusercontent.com/22703561/39804854-e104a71c-537d-11e8-9a13-5d96da3f890a.gif)


## Σύνδεσμοι πολυμεσικού υλικού
https://www.shutterstock.com/image-vector/glossy-round-buttons-badges-concerning-flags-348857168





