# agiobotics-21-22


Σύντομη περιγραφή:

Το fire - robot είναι η λύση στο πρόβλημα των πυρκαγιών. Πιο συγκεκριμένα αναφερόμαστε σε ένα σύστημα αισθητήρων (θερμότητας ή καπνού ) που θα είναι τοποθετημένο κοντά σε εύφλεκτες περιοχές. Το σύστημα έχει την ιδιότητα του πομπού στέλνοντας ένα μήνυμα «πυρκαγιάς» σε μια αντλία νερού. Το μήνυμα αυτό έχει ως στόχο την ενεργοποίηση λειτουργίας της αντλίας. Έτσι, η αντλία αρχίζει να μεταφέρει νερό προς την φλεγόμενη περιοχή που εντόπισε ο αισθητήρας. Η πράξη αυτή έχει ως αποτέλεσμα την κατάσβεση της φωτιάς. Τέλος, η αντλία απενεργοποιείται μόλις λάβει μήνυμα από τον αισθητήρα ότι η θερμοκρασία είναι και πάλι εντός των φυσιολογικών θερμοκρασιών της περιοχής.

Υλικά :
1 arduino uno
1 αντλία νερου  
2 αισθητηρες (καπνου - θερμοκρασιας)
1 breadboard
2 servo motors
1 κουμπι on/off
1 buzzer
αντιστάσεις
leds
μπαταριες
καλώδια με pins
Σωληνες μεταφορας νερου 

Η λειτουργία του fire-robot:
Η κατασκευή μας θα αποτελείται από ένα σύστημα επικοινωνίας αισθητήρων και αντλίας νερού. Οι αισθητήρες θα είναι υπεύθυνοι για τον έλεγχο των τιμών της θερμοκρασίας. Σε περίπτωση που ανιχνεύσουν υψηλές θερμοκρασίες ,εκτός του φυσιολογικού ορίου, θα επικοινωνούν με απευθύνονται σε μια αντλία νερού για την επίλυση του προβλήματος. Μόλις οι αισθητήρες στείλουν το «μήνυμα» αυτό, η αντλία νερού θα ενεργοποιηθεί. Με την ενεργοποίηση της αντλίας, θα αρχίσει η μεταφορά του νερού μέσω σωληνώσεων προς τον αισθητήρα που ανίχνευσε υψηλές θερμοκρασίες. Έτσι, θα αρχίσει η κατάσβεσή της φωτιάς λόγω του νερού. Όταν ο αισθητήρας λάβει και πάλι φυσιολογικές τιμές θερμοκρασίας θα στείλει ένα άλλο «μήνυμα» στην αντλία με σκοπό την απενεργοποίηση της. Η ρομποτική κατασκευή μας θα παραμένει ακίνητη λόγω μη ανάγκης κίνησης καθώς το αποτέλεσμα είναι το ίδιο ανταμειφτικό.

link video:
https://drive.google.com/file/d/1SI939ThNGYwNhoR-MX5xBL4uVIv1z0My/view

link tinkercad
https://www.tinkercad.com/embed/8LWwDjuROYf?editbtn=1
