---
title: Αποκεντρωμένη ταυτότητα
description: Αποκεντρωμένη ταυτότητα και η σημασία της
lang: el
template: use-cases
emoji: ":id:"
sidebarDepth: 2
image: /eth-gif-cat.png
summaryPoint1: Τα παραδοσιακά συστήματα ταυτότητας διαχειρίζονται κεντρικά τα στοιχεία και τον έλεγχο των αναγνωριστικών σας.
summaryPoint2: Η αποκεντρωμένη ταυτότητα καταργεί την ανάγκη ύπαρξης κεντρικών τρίτων μερών.
summaryPoint3: Χάρη στα κρυπτονομίσματα, οι χρήστες διαθέτουν εργαλεία έκδοσης, διατήρησης και ελέγχου των αναγνωριστικών τους και καθώς και της επικύρωσης.
---

Η ταυτότητα στηρίζει σχεδόν κάθε πτυχή της ζωής σας σήμερα. Η χρήση διαδικτυακών υπηρεσιών, το άνοιγμα τραπεζικού λογαριασμού, η ψηφοφορία στις εκλογές, η αγορά ακινήτων, η εξασφάλιση εργασίας—όλα αυτά απαιτούν απόδειξη της ταυτότητάς σας. Η χρήση διαδικτυακών υπηρεσιών, το άνοιγμα τραπεζικού λογαριασμού, η ψηφοφορία στις εκλογές, η αγορά ακινήτων, η εξασφάλιση εργασίας—όλα αυτά απαιτούν απόδειξη της ταυτότητάς σας.

Ωστόσο, τα παραδοσιακά συστήματα διαχείρισης ταυτοποίησης βασίζονται εδώ και πολύ καιρό σε κεντρικούς μεσάζοντες που εκδίδουν, κατέχουν και ελέγχουν τα αναγνωριστικά και [ τις βεβαιώσεις σας](#what-are-attestations). Αυτό σημαίνει ότι δεν μπορείτε να ελέγξετε τις πληροφορίες που σχετίζονται με την ταυτότητά σας ή να αποφασίσετε ποιος έχει πρόσβαση σε πληροφορίες προσωπικής ταυτοποίησης (PII) και πόση πρόσβαση έχουν αυτά τα μέλη.

Για να λύσουμε αυτά τα προβλήματα, έχουμε αποκεντρωμένα συστήματα ταυτότητας που είναι χτισμένα σε δημόσια blockchains όπως το Ethereum. Η αποκεντρωμένη ταυτότητα επιτρέπει στα ίδια τα άτομα να διαχειρίζονται τις πληροφορίες που σχετίζονται με την ταυτότητά τους. Με αποκεντρωμένες λύσεις ταυτότητας, _μπορείτε_ να δημιουργήσετε αναγνωριστικά και να διεκδικήσετε και να κρατήσετε τις βεβαιώσεις σας χωρίς να βασίζεστε σε κεντρικές αρχές, όπως παρόχους υπηρεσιών ή κυβερνήσεις.

## Τι είναι η ταυτότητα; {#what-is-identity}

Ταυτότητα σημαίνει η αίσθηση του εαυτού ενός ατόμου, που ορίζεται από μοναδικά χαρακτηριστικά. Η ταυτότητα αναφέρεται στο να είσαι ένα _άτομο _, δηλ. μια ξεχωριστή ανθρώπινη οντότητα. Η ταυτότητα θα μπορούσε επίσης να αναφέρεται σε άλλες μην ανθρώπινες οντότητες, όπως έναν οργανισμό ή μια αρχή.

## Τι είναι τα αναγνωριστικά; {#what-are-identifiers}

Το αναγνωριστικό είναι ένα κομμάτι πληροφορίας που ενεργεί ως δείκτης μιας συγκεκριμένης ταυτότητας ή ιδιότητας. Τα κοινά αναγνωριστικά περιλαμβάνουν:

- Όνομα
- Αριθμός κοινωνικής ασφάλισης/αριθμός φορολογικού μητρώου
- Αριθμός κινητού
- Ημερομηνία και τόπος γέννησης
- Ψηφιακά διαπιστευτήρια, π.χ. διευθύνσεις email, ονόματα χρηστών, άβαταρ

Αυτά τα παραδοσιακά παραδείγματα αναγνωριστικών εκδίδονται, διατηρούνται και ελέγχονται από κεντρικές αρχές. Χρειάζεστε άδεια από την κυβέρνησή σας για να αλλάξετε το όνομά σας ή και από μια πλατφόρμα κοινωνικών μέσων για να αλλάξετε το όνομα χρήστη σας.

## Τι είναι οι βεβαιώσεις; {#what-are-attestations}

Μια βεβαίωση είναι μια ισχυρισμός που διατυπώνεται από μια οντότητα για μια άλλη οντότητα. Εάν ζείτε στις Ηνωμένες Πολιτείες, η άδεια οδήγησης που σας έχει εκδοθεί από το Υπουργείο Μηχανοκίνητων Οχημάτων (μία οντότητα) βεβαιώνει ότι εσείς (μια άλλη οντότητα) επιτρέπεται νόμιμα να οδηγείτε αυτοκίνητο.

Οι βεβαιώσεις διαφέρουν από τα αναγνωριστικά. Μια βεβαίωση _περιέχει_ αναγνωριστικά για την αναφορά μιας συγκεκριμένης ταυτότητας και προβάλλει έναν ισχυρισμό σχετικά με ένα χαρακτηριστικό που σχετίζεται με αυτήν την ταυτότητα. Έτσι, η άδεια οδήγησής σας έχει αναγνωριστικά (όνομα, ημερομηνία γέννησης, διεύθυνση) αλλά είναι και η βεβαίωση σχετικά με το νόμιμο δικαίωμα οδήγησης σας.

### Τι είναι τα αποκεντρωμένα αναγνωριστικά; {#what-are-decentralized-identifiers}

Τα παραδοσιακά αναγνωριστικά όπως το νόμιμο όνομα ή η διεύθυνση ηλεκτρονικού ταχυδρομείου σας, βασίζονται σε τρίτα μέρη—κυβερνήσεις και παρόχους ηλεκτρονικών διευθύνσεων. Τα αποκεντρωμένα αναγνωριστικά (DID) είναι διαφορετικά—δεν εκδίδονται, διαχειρίζονται ή ελέγχονται από καμία κεντρική οντότητα.

Τα αποκεντρωμένα αναγνωριστικά εκδίδονται, διατηρούνται και ελέγχονται από άτομα. Ένας [λογαριασμός Ethereum](/developers/docs/accounts/) είναι ένα παράδειγμα αποκεντρωμένου αναγνωριστικού. Μπορείτε να δημιουργήσετε όσους λογαριασμούς θέλετε χωρίς άδεια από κανέναν και χωρίς να χρειάζεται να τους αποθηκεύσετε σε κεντρικό αρχείο.

Τα αποκεντρωμένα αναγνωριστικά αποθηκεύονται σε διανέμομενα λογιστικά βιβλία (blockchains) ή δίκτυα peer-to-peer. Αυτό καθιστά τα DID [παγκοσμίως μοναδικά, επιλύσιμα με υψηλή διαθεσιμότητα και κρυπτογραφικά επαληθεύσιμα](https://w3c-ccg.github.io/did-primer/). Ένα αποκεντρωμένο αναγνωριστικό μπορεί να συσχετιστεί με διαφορετικές οντότητες, συμπεριλαμβανομένων ατόμων, οργανισμών ή κυβερνητικών ιδρυμάτων.

## Τι καθιστά τα αποκεντρωμένα αναγνωριστικά υλοποιήσιμα; {#what-makes-decentralized-identifiers-possible}

### 1. Υποδομή Δημόσιου Κλειδιού (PKI) {#public-key-infrastructure}

Το Public-key infrastructure (PKI) είναι ένα μέτρο ασφάλειας πληροφοριών που δημιουργεί ένα [δημόσιο κλειδί](/glossary/#public-key) και [ ένα ιδιωτικό κλειδί](/glossary/#private-key) για μια οντότητα. Η κρυπτογραφία δημόσιου κλειδιού χρησιμοποιείται σε δίκτυα blockchain για τον έλεγχο ταυτότητας των χρηστών και την απόδειξη της ιδιοκτησίας των ψηφιακών τους στοιχείων.

Ορισμένα αποκεντρωμένα αναγνωριστικά, όπως ένας λογαριασμός Ethereum, διαθέτουν δημόσια και ιδιωτικά κλειδιά. Το δημόσιο κλειδί προσδιορίζει τον διαχειριστή του λογαριασμού, ενώ τα ιδιωτικά κλειδιά μπορούν να υπογράψουν και να αποκρυπτογραφήσουν μηνύματα για αυτόν τον λογαριασμό. Το PKI παρέχει αποδείξεις που απαιτούνται για τον έλεγχο ταυτότητας οντοτήτων και την αποτροπή πλαστοπροσωπίας και χρήσης πλαστών ταυτοτήτων, χρησιμοποιώντας τις [κρυπτογραφημένες υπογραφές](https://andersbrownworth.com/blockchain/public-private-keys/) για την επαλήθευση όλων των ενεργειών.

### 2. Αποκεντρωμένα συστήματα δεδομένων {#decentralized-datastores}

Μία blockchain χρησιμεύει ως ένα μητρώο δεδομένων που μπορεί να επαληθευτεί: δηλαδή ένα ανοιχτό, αξιόπιστο και αποκεντρωμένο αποθετήριο πληροφοριών. Η ύπαρξη δημόσιων blockchain εξαλείφει την ανάγκη αποθήκευσης αναγνωριστικών σε κεντρικά μητρώα.

Εάν κάποιος χρειάζεται να επιβεβαιώσει την εγκυρότητα ενός αποκεντρωμένου αναγνωριστικού, μπορεί να αναζητήσει το σχετικό δημόσιο κλειδί στο blockchain. Αυτό διαφέρει από τα παραδοσιακά αναγνωριστικά που απαιτούν έλεγχο ταυτότητας από τρίτους.

## Πώς τα αποκεντρωμένα αναγνωριστικά και οι βεβαιώσεις επιτρέπουν την αποκεντρωμένη ταυτότητα; {#how-decentralized-identifiers-and-attestations-enable-decentralized-identity}

Η αποκεντρωμένη ταυτότητα είναι η ιδέα ότι οι πληροφορίες που σχετίζονται με την ταυτότητα πρέπει να είναι αυτοελεγχόμενες, απόρρητες και φορητές, με τα αποκεντρωμένα αναγνωριστικά και τις βεβαιώσεις να είναι τα κύρια δομικά τους στοιχεία.

Στο πλαίσιο της αποκεντρωμένης ταυτότητας, οι βεβαιώσεις (επίσης γνωστές ως [Επαληθεύσιμα διαπιστευτήρια](https://www.w3.org/TR/vc-data-model/)) είναι στεγανές, κρυπτογραφικά επαληθεύσιμα από όλους. Κάθε βεβαίωση ή επαληθεύσιμο διαπιστευτήριο που εκδίδει μια οντότητα (π.χ. ένας οργανισμός) σχετίζεται με το DID της.

Επειδή τα DID αποθηκεύονται στο blockchain, οποιοσδήποτε μπορεί να επαληθεύσει την εγκυρότητα μιας βεβαίωσης ελέγχοντας το DID του εκδότη στο Ethereum. Ουσιαστικά, το blockchain του Ethereum λειτουργεί σαν ένας παγκόσμιος κατάλογος που επιτρέπει την επαλήθευση των DID που σχετίζονται με συγκεκριμένες οντότητες.

Τα αποκεντρωμένα αναγνωριστικά είναι ο λόγος που οι βεβαιώσεις είναι αυτοελεγχόμενες και επαληθεύσιμες. Ακόμα και αν ο εκδότης δεν υπάρχει πλέον, ο κάτοχος έχει πάντα την απόδειξη της προέλευσης και της εγκυρότητας της βεβαίωσης.

Τα αποκεντρωμένα αναγνωριστικά είναι επίσης ζωτικής σημασίας για την προστασία του απορρήτου των προσωπικών πληροφοριών, μέσω της αποκεντρωμένης ταυτότητας. Για παράδειγμα, εάν ένα άτομο υποβάλει αποδεικτικό βεβαίωσης (άδεια οδήγησης), το μέρος επαλήθευσης δε χρειάζεται να ελέγξει την εγκυρότητα των πληροφοριών στο αποδεικτικό. Αντίθετα, ο επαληθευτής χρειάζεται μόνο κρυπτογραφημένες εγγυήσεις για τη γνησιότητα της βεβαίωσης και την ταυτότητα του οργανισμού που εκδίδει για να καθορίσει εάν η απόδειξη είναι έγκυρη.

## Τύποι βεβαιώσεων αποκεντρωμένης ταυτότητας {#types-of-attestations-in-decentralized-identity}

Ο τρόπος με τον οποίο αποθηκεύονται και ανακτώνται οι πληροφορίες βεβαίωσης σε ένα οικοσύστημα ταυτότητας που βασίζεται στο Ethereum, διαφέρει από την παραδοσιακή διαχείριση ταυτότητας. Ακολουθεί μια επισκόπηση διαφορετικών προσεγγίσεων για την έκδοση, την αποθήκευση και την επαλήθευση βεβαιώσεων σε αποκεντρωμένα συστήματα ταυτότητας:

### Βεβαιώσεις εκτός αλυσίδας {#off-chain-attestations}

Μια ανησυχία σχετικά με την αποθήκευση βεβαιώσεων στην αλυσίδα είναι ότι μπορεί να περιέχουν πληροφορίες που οι χρήστες θέλουν να διατηρήσουν ιδιωτικά. Ο δημόσιος χαρακτήρας του blockchain Ethereum καθιστά μη ελκυστική την αποθήκευση τέτοιων βεβαιώσεων.

Η λύση είναι η έκδοση βεβαιώσεων, που τηρούνται από χρήστες εκτός αλυσίδας σε ψηφιακά πορτοφόλια, αλλά υπογεγραμμένες με το DID του εκδότη που είναι αποθηκευμένο στην αλυσίδα. Αυτές οι βεβαιώσεις κωδικοποιούνται ως [JSON Web Tokens](https://en.wikipedia.org/wiki/JSON_Web_Token) και περιέχουν την ψηφιακή υπογραφή του εκδότη, η οποία επιτρέπει την εύκολη επαλήθευση πληροφοριών εκτός αλυσίδας.

Ακολουθεί ένα υποθετικό σενάριο που εξηγεί τις βεβαιώσεις εκτός αλυσίδας:

1. Ένα πανεπιστήμιο (ο εκδότης) δημιουργεί μια βεβαίωση (ψηφιακό ακαδημαϊκό πιστοποιητικό), υπογράφει με τα κλειδιά του και την εκδίδει για τον Μπομπ (τον κάτοχο της ταυτότητας).

2. Ο Μπομπ κάνει αίτηση για δουλειά και θέλει να αποδείξει τα ακαδημαϊκά του προσόντα σε έναν εργοδότη, γι' αυτό μοιράζεται τη βεβαίωση από το κινητό του πορτοφόλι. Η εταιρεία (ο επαληθευτής) μπορεί στη συνέχεια να επιβεβαιώσει την εγκυρότητα της βεβαίωσης ελέγχοντας το DID του εκδότη (δηλαδή το δημόσιο κλειδί του στο Ethereum).

### Βεβαιώσεις εκτός αλυσίδας με μόνιμη πρόσβαση {#offchain-attestations-with-persistent-access}

Σύμφωνα με αυτήν τη ρύθμιση, οι βεβαιώσεις μετατρέπονται σε αρχεία JSON και αποθηκεύονται εκτός αλυσίδας (ιδανικά σε μια πλατφόρμα [αποκεντρωμένης αποθήκευσης cloud](/developers/docs/storage/), όπως το IPFS ή το Swarm). Ωστόσο, ένα [αναγνωριστικό](/glossary/#hash) του αρχείου JSON αποθηκεύεται στην αλυσίδα και συνδέεται με ένα DID μέσω ενός μητρώου σε αυτή. Το σχετικό DID μπορεί να είναι είτε του εκδότη της βεβαίωσης είτε του παραλήπτη.

Αυτή η προσέγγιση επιτρέπει στις βεβαιώσεις να αποκτήσουν διάρκεια με βάση το blockchain, διατηρώντας παράλληλα τις πληροφορίες των αξιώσεων κρυπτογραφημένες και επαληθεύσιμες. Επιτρέπει επίσης την επιλεκτική αποκάλυψη, καθώς ο κάτοχος του ιδιωτικού κλειδιού μπορεί να αποκρυπτογραφήσει τις πληροφορίες.

### Βεβαιώσεις επί της αλυσίδας {#onchain-attestations}

Οι βεβαιώσεις επί της αλυσίδας πραγματοποιούνται στα [έξυπνα συμβόλαια](/developers/docs/smart-contracts/) στο blockchain του Ethereum. Το έξυπνο συμβόλαιο (που λειτουργεί ως μητρώο) θα αντιστοιχίσει μια βεβαίωση σε ένα αντίστοιχο αποκεντρωμένο αναγνωριστικό στην αλυσίδα (ένα δημόσιο κλειδί).

Ακολουθεί ένα παράδειγμα για να δείτε πώς οι βεβαιώσεις στην αλυσίδα λειτουργούν στην πράξη:

1. Μια εταιρεία (XYZ Corp) σχεδιάζει να πουλήσει μετοχές ιδιοκτησίας χρησιμοποιώντας ένα έξυπνο συμβόλαιο, αλλά θέλει μόνο αγοραστές που έχουν ολοκληρώσει έναν έλεγχο.

2. Η XYZ Corp μπορεί να ζητήσει από την εταιρεία να πραγματοποιεί ελέγχους ζητημάτων για την έκδοση πιστοποιήσεων επί της αλυσίδας στο Ethereum. Αυτή η βεβαίωση πιστοποιεί ότι ένα άτομο έχει περάσει τον έλεγχο χωρίς να αποκαλύψει τα προσωπικά στοιχεία του.

3. Το έξυπνο συμβόλαιο της πώλησης μετοχών μπορεί να ελέγξει το συμβόλαιο μητρώου για τις ταυτότητες των αγοραστών που έχουν ελεγχθεί, καθιστώντας δυνατό να προσδιορίσει ποιος επιτρέπεται να αγοράσει μετοχές ή όχι.

### Προσωπικά ψηφιακά στοιχεία και ταυτότητα {#soulbound}

Τα [προσωπικά ψηφιακά στοιχεία](https://vitalik.ca/general/2022/01/26/soulbound.html) (μη μεταβιβάσιμα NFT) θα μπορούσαν να χρησιμοποιηθούν για τη συλλογή μοναδικών πληροφοριών για ένα συγκεκριμένο πορτοφόλι. Αυτό δημιουργεί αποτελεσματικά μια μοναδική ταυτότητα επί της αλυσίδας που συνδέεται με μια συγκεκριμένη διεύθυνση Ethereum που θα μπορούσε να περιλαμβάνει ψηφιακά στοιχεία που αντιπροσωπεύουν επιτεύγματα (π.χ. ολοκλήρωση κάποιου συγκεκριμένου διαδικτυακού μαθήματος ή μιας βαθμολογίας σε ένα παιχνίδι) ή συμμετοχή στην κοινότητα.

## Πλεονεκτήματα της αποκεντρωμένης ταυτότητας {#benefits-of-decentralized-identity}

1. Η αποκεντρωμένη ταυτότητα αυξάνει τον ατομικό έλεγχο των πληροφοριών αναγνώρισης. Τα αποκεντρωμένα αναγνωριστικά και οι βεβαιώσεις μπορούν να επαληθευτούν χωρίς να βασίζεστε σε κεντρικές αρχές και υπηρεσίες τρίτων.

2. Οι αποκεντρωμένες λύσεις ταυτότητας διευκολύνουν μια αξιόπιστη, απρόσκοπτη και προστατευτική μέθοδο για την επαλήθευση και τη διαχείριση της ταυτότητας χρήστη.

3. Η αποκεντρωμένη ταυτότητα αξιοποιεί την τεχνολογία blockchain, η οποία δημιουργεί εμπιστοσύνη μεταξύ των διαφορετικών μερών και παρέχει κρυπτογραφημένες εγγυήσεις για την απόδειξη της εγκυρότητας των βεβαιώσεων.

4. Η αποκεντρωμένη ταυτότητα καθιστά τα δεδομένα ταυτότητας φορητά. Οι χρήστες αποθηκεύουν τις βεβαιώσεις και τα αναγνωριστικά στο πορτοφόλι του τηλεφώνου τους και μπορούν να τα μοιραστούν με οποιονδήποτε επιλέξουν. Τα αποκεντρωμένα αναγνωριστικά και οι βεβαιώσεις δεν είναι κλειδωμένα στη βάση δεδομένων του οργανισμού έκδοσης.

5. Η αποκεντρωμένη ταυτότητα θα πρέπει να λειτουργεί καλά με τις αναδυόμενες τεχνολογίες μηδενικής γνώσης που θα επιτρέψουν στα άτομα να αποδείξουν ότι κατέχουν ή έχουν κάνει κάτι χωρίς να αποκαλύπτουν τι είναι αυτό. Αυτό θα μπορούσε να γίνει ένας ισχυρός τρόπος για να συνδυαστεί η εμπιστοσύνη και το απόρρητο για εφαρμογές όπως η ψηφοφορία.

6. Η αποκεντρωμένη ταυτότητα επιτρέπει στους μηχανισμούς anti-Sybil να αναγνωρίζουν πότε ένας μεμονωμένος άνθρωπος προσποιείται ότι είναι πολλοί άνθρωποι για να παίξει ή να στείλει κακόβουλο περιεχόμενο σε κάποιο σύστημα.

## Χρήσεις αποκεντρωμένης ταυτότητας {#decentralized-identity-use-cases}

Η αποκεντρωμένη ταυτότητα έχει πολλές περιπτώσεις χρήσης όπως:

### 1. Γενική σύνδεση {#universal-dapp-logins}

Η αποκεντρωμένη ταυτότητα μπορεί να βοηθήσει στην αντικατάσταση των συνδέσεων που βασίζονται σε κωδικό πρόσβασης με [αποκεντρωμένο έλεγχο ταυτότητας](https://www.ibm.com/blogs/blockchain/2018/10/decentralized-identity-an-alternative-to-password-based-authentication/). Οι πάροχοι υπηρεσιών μπορούν να εκδίδουν βεβαιώσεις στους χρήστες, οι οποίες μπορούν να αποθηκευτούν σε ένα πορτοφόλι Ethereum. Ένα παράδειγμα βεβαίωσης θα ήταν ένα [NFT](/nft/) που παρέχει στον κάτοχο πρόσβαση σε μια διαδικτυακή κοινότητα.

Μια λειτουργία [Σύνδεση με Ethereum](https://login.xyz/) θα επέτρεπε στους διακομιστές να επιβεβαιώσουν τον λογαριασμό Ethereum του χρήστη και να ανακτήσουν την απαιτούμενη βεβαίωση από τη διεύθυνση του λογαριασμού τους. Αυτό σημαίνει ότι οι χρήστες μπορούν να έχουν πρόσβαση σε πλατφόρμες και ιστότοπους χωρίς να χρειάζεται να απομνημονεύουν μεγάλους κωδικούς πρόσβασης βελτιώνοντας τη διαδικτυακή εμπειρία.

### 2. Πιστοποίηση KYC {#kyc-authentication}

Η χρήση πολλών διαδικτυακών υπηρεσιών απαιτεί από τα άτομα να παρέχουν πιστοποιήσεις και διαπιστευτήρια, όπως άδεια οδήγησης ή διαβατήριο. Ωστόσο, αυτή η προσέγγιση είναι προβληματική επειδή οι ιδιωτικές πληροφορίες χρήστη, μπορεί να παραβιαστούν και οι πάροχοι υπηρεσιών δεν μπορούν να επαληθεύσουν τη γνησιότητα της πιστοποίησης.

Η αποκεντρωμένη ταυτότητα επιτρέπει στις εταιρείες να παρακάμπτουν τις συμβατικές διαδικασίες [Know-Your-Customer (KYC)](https://en.wikipedia.org/wiki/Know_your_customer) και να ελέγχουν την ταυτότητα των χρηστών μέσω επαληθεύσιμων διαπιστευτηρίων. Αυτό μειώνει το κόστος διαχείρισης ταυτότητας και αποτρέπει τη χρήση πλαστών εγγράφων.

### 3. Ψηφοφορίες και διαδικτυακές κοινότητες {#voting-and-online-communities}

Η διαδικτυακή ψηφοφορία και τα μέσα κοινωνικής δικτύωσης είναι δύο νέες εφαρμογές για αποκεντρωμένη ταυτότητα. Τα διαδικτυακά συστήματα ψηφοφορίας είναι επιρρεπή σε χειραγώγηση, ειδικά εάν κακόβουλοι παράγοντες δημιουργούν ψευδείς ταυτότητες για να ψηφίσουν. Ζητώντας από άτομα να παρουσιάσουν βεβαιώσεις on-chain μπορεί να βελτιώσει την ακεραιότητα των διαδικτυακών διαδικασιών ψηφοφορίας.

Η αποκεντρωμένη ταυτότητα μπορεί να βοηθήσει στη δημιουργία διαδικτυακών κοινοτήτων χωρίς ψεύτικους λογαριασμούς. Για παράδειγμα, κάθε χρήστης μπορεί να χρειαστεί να πιστοποιήσει την ταυτότητά του χρησιμοποιώντας ένα σύστημα ταυτότητας on-chain, όπως η υπηρεσία ονομάτων Ethereum, μειώνοντας την πιθανότητα από ρομπότ.

### 4. Προστασία Anti-Sybil {#sybil-protection}

Οι επιθέσεις Sybil αναφέρονται σε μεμονωμένους ανθρώπους που ξεγελούν ένα σύστημα ώστε να πιστεύουν ότι είναι πολλά άτομα για να αυξήσουν την επιρροή τους. Οι [εφαρμογές παροχής επιχορηγήσεων](https://gitcoin.co/grants/) που χρησιμοποιούν [ την τετραγωνική ψηφοφορία](https://www.radicalxchange.org/concepts/plural-voting/) είναι ευάλωτα σε αυτές τις επιθέσεις Sybil, επειδή η αξία μιας επιχορήγησης αυξάνεται όταν περισσότερα άτομα την ψηφίζουν, παροτρύνοντας τους χρήστες να μοιράσουν τις συνεισφορές τους σε πολλές ταυτότητες. Οι αποκεντρωμένες ταυτότητες βοηθούν να αποφευχθεί κάτι τέτοιο, αυξάνοντας το βάρος σε κάθε συμμετέχοντα να αποδείξει ότι είναι πραγματικά άνθρωπος, αν και συχνά χωρίς να χρειάζεται να αποκαλύψει συγκεκριμένες προσωπικές πληροφορίες.

## Χρήση αποκεντρωμένης ταυτότητας {#use-decentralized-identity}

Υπάρχουν πολλά φιλόδοξα έργα που χρησιμοποιούν το Ethereum ως βάση για αποκεντρωμένες λύσεις ταυτότητας:

- **[Υπηρεσία ονόματος Ethereum (ENS)](https://ens.domains/)** - _ Ένα αποκεντρωμένο σύστημα ονοματοδοσίας για αναγνωριστικά εντός αλυσίδας, αναγνώσιμα από μηχανή, όπως διευθύνσεις πορτοφολιού Ethereum, κατακερματισμοί περιεχομένου και μεταδεδομένα._
- **[SpruceID](https://www.spruceid.com/)** - _Ένα έργο για αποκεντρωμένη ταυτότητα που επιτρέπει στους χρήστες να ελέγχουν την ψηφιακή ταυτότητα με λογαριασμούς Ethereum και προφίλ ENS αντί να βασίζονται σε υπηρεσίες τρίτων._
- **[Υπηρεσία Επικύρωσης Ethereum (EAS)](https://attest.sh/)** - _Ένα αποκεντρωμένο ledger/πρωτόκολλο για την κατασκευή βεβαιώσεων επί ή εκτός της αλυσίδας για οτιδήποτε._
- **[Απόδειξη ότι είσαι Άνθρωπος](https://www.proofofhumanity.id)** - _Η απόδειξη ότι είσαι Άνθρωπος (ή PoH) είναι ένα κοινωνικό σύστημα επαλήθευσης ταυτότητας που βασίζεται στο Ethereum._
- **[BrightID](https://www.brightid.org/)** - _Αποκεντρωμένο, δίκτυο κοινωνικής ταυτότητας ανοιχτού κώδικα που επιδιώκει να μεταρρυθμίσει την επαλήθευση ταυτότητας μέσω της δημιουργίας και ανάλυσης ενός κοινωνικού γραφήματος._
- **[Διαβατήριο απόδειξης προσωπικότητας](https://proofofpersonhood.com/)** - _Ένας αποκεντρωμένος φορέας συγκέντρωσης ψηφιακών ταυτοτήτων._

## Περισσότερες πληροφορίες {#further-reading}

### Άρθρα {#articles}

- [Περιπτώσεις χρήσης Blockchain: Blockchain στην ψηφιακή ταυτότητα](https://consensys.net/blockchain-use-cases/digital-identity/) — _ConsenSys_
- [Τι είναι το Ethereum ERC725; Ανεξάρτητη διαχείριση ταυτότητας στο Blockchain](https://cryptoslate.com/what-is-erc725-self-sovereign-identity-management-on-the-blockchain/) — _Sam Town_
- [Πώς το Blockchain θα μπορούσε να λύσει το πρόβλημα της ψηφιακής ταυτότητας](https://time.com/6142810/proof-of-humanity/) — _Andrew R. Τσόου_
- [Τι είναι η αποκεντρωμένη ταυτότητα και γιατί πρέπει να σας ενδιαφέρει;](https://web3.hashnode.com/what-is-decentralized-identity) — _Emmanuel Awosika_

### Βίντεο {#videos}

- [Αποκεντρωμένη ταυτότητα (Bonus Livestream Session)](https://www.youtube.com/watch?v=ySHNB1za_SE&t=539s) — _Ένα υπέροχο επεξηγητικό βίντεο για την αποκεντρωμένη ταυτότητα από τον Ανδρέα Αντωνόπουλο_
- [Συνδεθείτε με το Ethereum και την αποκεντρωμένη ταυτότητα με Ceramic, IDX, React και 3ID Connect](https://www.youtube.com/watch?v=t9gWZYJxk7c) — _Οδηγός YouTube σχετικά με τη δημιουργία ενός συστήματος διαχείρισης ταυτότητας για τη δημιουργία, την ανάγνωση και την ενημέρωση του προφίλ ενός χρήστη χρησιμοποιώντας το πορτοφόλι του Ethereum από τον Nader Dabit_
- [BrightID - Αποκεντρωμένη ταυτότητα στο Ethereum](https://www.youtube.com/watch?v=D3DbMFYGRoM) — _Επεισόδιο podcast χωρίς τράπεζα που συζητά το BrightID, μια αποκεντρωμένη λύση ταυτότητας για το Ethereum_
- [Το Διαδίκτυο εκτός αλυσίδας: Αποκεντρωμένη ταυτότητα & Επαληθεύσιμα διαπιστευτήρια](https://www.youtube.com/watch?v=EZ_Bb6j87mg) — Παρουσίαση EthDenver 2022 από την Evin McMullen

### Κοινότητες {#communities}

- [ERC-725 Alliance στο GitHub](https://github.com/erc725alliance) — _Υποστηρικτές του προτύπου ERC725 για τη διαχείριση ταυτότητας στο blockchain Ethereum_
- [Διακομιστής SpruceID Discord](https://discord.com/invite/Sf9tSFzrnt) — _Κοινότητα για λάτρεις και προγραμματιστές που εργάζονται με τον τρόπο Σύνδεσης στο Ethereum_
- [Veramo Labs](https://discord.gg/sYBUXpACh4) — _Μια κοινότητα προγραμματιστών που συμβάλλουν στη δημιουργία ενός πλαισίου για επαληθεύσιμα δεδομένα για εφαρμογές_