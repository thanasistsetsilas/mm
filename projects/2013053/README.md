# ΙΟΝΙΟ ΠΑΝΕΠΙΣΤΗΜΙΟ, ΤΜΗΜΑ ΠΛΗΡΟΦΟΡΙΚΗΣ 

## ΜΑΘΗΜΑ
### Πολυμέσα  
Επιβλέπων καθηγητής: Χωριανόπουλος Κωνσταντίνος  

## Επιλογή Εργασίας   
### Shooter ([https://github.com/ioniodi/shooter](https://github.com/ioniodi/shooter))
## Στοιχεία φοιτητή  
### Παναγιώτης Κορμπάς  
### ΑΜ: Π2013053  
### Εκτελέσιμο: [https://p13korb.github.io/Shooter/](https://p13korb.github.io/Shooter/)  
### Αποθετήριο κώδικα: [https://github.com/p13korb/Shooter](https://github.com/p13korb/Shooter)  
### Αποθετήριο ιστοσελίδας εργασίας περιεχομένου: [https://github.com/p13korb/gr](https://github.com/p13korb/gr)  
### Σελιδα αναφοράς: [https://p13korb.github.io/anafora_mm/](https://p13korb.github.io/anafora_mm/)

## Εισαγωγή  
Σκοπος της εργασιας αυτης ηταν να παρουμε τις οδηγιες ενος tutorial και βασιζομενοι σε αυτο και στις οδιγιες της εργασιας να κανουμε αλλαγες και να προσθεσουμε καποια παραπανω πραγματα. Το παιχνδιδι ηταν ενα κλασσικο space arcade minigame που σκοπο ειχε την επιτευξη οσο το δυντον μεγαλυτερου score. Η εργασια εγινε χρησιμοποιοντας την γλωσσα προγραμματισμου javascript και το framework phaser v2.6.2.

## Μέθοδος αναπτυξης  
Το σκεπτικο αναπτυξης της παρουσας εργασιας εχει ως εξης. Υπαρχουν δυο πιστες. Στην πρωτη πιστα, ο παικτης μολις φτασει σε ενα ενα οριο score εμφανιζεται το τελικο boss. Επισης, κατα την αρχη της πρωτης πιστας, δινεται η δυνατοτητα στον παικτη να παρει ενα αντικειμενο powerup το οποιο εμφανιζεται μονο μια φορα και ακολουθει την φορα τον αντιπαλων σκαφων. Αφοτου ο χρηστης σκοτωσει το boss, και συνεχισει με επιτυχια μεχρι το score 40000, τοτε αυτοματα το παιχνιδι συνεχιζει στο δευτερο επιπεδο. Το δευτερο επιπεδο ειναι σαφως πιο δυσκολο απο το πρωτο για τον λογο οτι οι εχθροι ερχονται με μεγαλυτερη συχνοτητα και ειναι περισσοτεροι στον αριθμο. Επιπλεον, προστεθηκαν καινουριοι εχθροι, οι κοκκινοι πλανητες. Σε αυτο το επιπεδο, το powerup ερχεται με μεγαλυτερη διαρκεια. Αν ο παικτης παρει μια φορα το αντικειμενο poweup, τοτε τα οπλα αναβαθμιζονται για πρωτη φορα. Οσο ακομη το powerup συνεχιζει να ερχεται, o παικτης μπορει να το ξαναπαρει για μια φορα ακομη. Η τελευταια φορα ειναι η τριτη με τον συνολικο αριθμο weapon upgrades να ανερχεται στους 3. Επιπλεον το boss ειναι διαφορετικο και αρκετα πιο δυσκολο στο να σκοτωθει. Το παιχνιδι τερματιζει οταν ο παικτης φτασει το score των 100000.

## Παραδοτέα
### Παραδοτέο 1ο  
- [x] Initial settings (όπως περιγράφονται στο README.md του repository)
- [x] Link του παιχνιδιού στην αναφορά
- [x] Πρόσθεσε ήχους (shooting, explosions, κτλ.) και μουσική.
- [x] Πρόσθεσε την πρώτη κατηγορία εχθρών σύμφωνα με τα steps 12-17 από τις οδηγίες. Για την συγκεκριμένη κατηγορία εχθρών χρησιμοποίησε την εικόνα enemy2.png αντί για την εικόνα green-enemy.png. Προσοχή: πρέπει να μελετήσετε τον κώδικα και να τον τροποποιήσετε κατάλληλα ώστε η συμπεριφορά των εχθρών να είναι ίδια αλλά να έρχονται από τα δεξιά προς τα αριστερά της οθόνης και όχι από πάνω προς τα κάτω όπως περιγράφετε στις οδηγίες.
- [x] Επέκτεινε το παιχνίδι ώστε να προσθέσεις ζωή και score ακολουθώντας τα steps 18-20 από τις οδηγίες.
- [x] Ακολούθησε το step 21 από τις οδηγίες. Προσοχή: πρέπει να δημιουργήσεις από εδώ και να χρησιμοποιήσεις το δικό σου font .
- [x] Πρόσθεσε τη δεύτερη κατηγορία εχθρών σύμφωνα με τα steps 22-24 από τις οδηγίες. Για τη συγκεκριμένη κατηγορία εχθρών χρησιμοποίησε την εικόνα enemy3.png αντί για την εικόνα blue-enemy.png. Προσοχή: πρέπει να μελετήσετε τον κώδικα και να τον τροποποιήσετε κατάλληλα ώστε η συμπεριφορά των εχθρών να είναι ίδια αλλά να έρχονται από τα δεξιά προς τα αριστερά της οθόνης και όχι από πάνω προς τα κάτω όπως περιγράφετε στις οδηγίες.
### Παραδοτέο 2ο  
- [x] Επεκτείνετε το παιχνίδι ώστε να αναβαθμίζονται τα όπλα του παίχτη σύμφωνα με τα steps 25-26 από τις οδηγίες. Προσοχή: πρέπει να μελετήσετε τον κώδικα και να τον τροποποιήσετε κατάλληλα ώστε η αναβάθμιση να μην γίνεται σύμφωνα με το score αλλά όταν ο παίχτης συλλέγει κάποιο αντικείμενο που εμφανίζεται στην πίστα. Επίσης να υπάρχουν παραπάνω από δυο κατηγορίες αναβαθμίσεων. Επιπλέον tutorial.
- [x] Προσθήκη Μenu στην αρχή για επιλογή πίστας και start of level. Δημιουργία τουλάχιστον δυο συνεχόμενων levels. Όταν ο πρωταγωνιστής ολοκληρώνει με επιτυχία το πρώτο level το παιχνίδι να συνεχίζει στο επόμενο. Το δεύτερο level θα πρέπει να είναι δυσκολότερο και να χρησιμοποιήσετε διαφορετικούς εχθρούς (new enemies, asteroids κτλ.). Μπορείτε να μελετήσετε τον κώδικα μιας περσινής εξαιρετικής εργασίας για να πάρετε μια ιδέα πως μπορείτε να υλοποιήσετε το συγκεκριμένο ζητούμενο.
- [x] Προσθήκη ενός μεγάλου εχθρού στο τέλος του level. Μια ιδέα μπορείτε να πάρετε από εδώ. Είστε ελεύθεροι να επιλέξετε την εικόνα και τη συμπεριφορά του μεγάλου εχθρού.
- [x] Τελική αναφορά την εργασίας που θα πρέπει απαραίτητα να περιλαμβάνει link του παιχνιδιού.  

## Συμπεράσματα  
Η παρουσα εργασια ηταν μια πολυ καλη ευκαιρια στο να εγκλιματιστουμε με την αναπτυξη βιντεοπαιχνιδιων για ιστοσελιδες χρησιμοποιοντας το phaser. Γενικοτερα, ο βαθμος δυσκολιας ηταν μετριος ωστοσο η διαδικασια αναπτυξης της εργασιας αρκετα διασκεδαστικη. Τελος μπορω να πω με σιγουρια πως η εργασια ηταν και αρκετα επιμορφωτικη.

## Screenshots

Menu  
![screenshot](https://raw.githubusercontent.com/p13korb/mm/2013053/projects/2013053/menu.png)  

Level 1  
![screenshot](https://raw.githubusercontent.com/p13korb/mm/2013053/projects/2013053/level1.png)  

Level 2  
![screenshot](https://raw.githubusercontent.com/p13korb/mm/2013053/projects/2013053/level2.png)