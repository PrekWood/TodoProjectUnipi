# Todo API (Software as a service)

Το παρακάτω API αποτελεί την εργασία για το μάθημα Software as a service του Πανεπιστημίου Πειραιώς


## Ομάδα

Πρέκας Νικόλαος Π18130

Ηλίας Μπρίνιας Π18112

Μήτσος Νικόλαος Π18102



##  Σύντομη περιγραφή

Το API δημιουργήθηκε πάνω στο framework της Ruby on Rails (v.7.0.2.2), ώς βάση δεδομένων χρησιμοποιήθηκε η MySQL (v.8.0.28), ενώ προκειμένου να υλοποιηθεί το πρότυπο του Test driven development χρησιμοποιήθηκε το gem Rspec (v.3.11) του Rails (Όλα τα tests θα τα βρείτε στο directory /spec). Για το deployment της εφαρμογής χρησιμοποιήθηκε το Heroku. Τον κώδικα του project θα τον βρείτε στο github.

https://github.com/PrekWood/TodoProjectUnipi

##  Οpenapi SWAGGER Documentation

https://app.swaggerhub.com/apis/PrekWood/TodoAPIUnipi/1.0.0-oas3


##  Παραδοχές

Για την ευκολότερη διαχείρηση των παραμέτρων στους controllers και προκειμένου οι κλήσεις στο API μας να έχουν το επιθυμητό REST format, παρακάμψαμε την λογική των strong parameters της Rails και εφαρμόσαμε το δικό μας validation στις παραμέτρους του API.