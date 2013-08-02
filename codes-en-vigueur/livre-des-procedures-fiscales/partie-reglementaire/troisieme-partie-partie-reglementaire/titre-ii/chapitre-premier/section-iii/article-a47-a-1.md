# Article A47 A-1

I.-Les copies mentionnées au I de l'article L. 47 A sont transmises, sous forme de fichiers à plat, à organisation séquentielle et structure zonée remplissant les critères suivants :

1° Les enregistrements sont séparés par le caractère de contrôle Retour chariot et/ ou Fin de ligne ;

2° Ils peuvent être de type mono ou multistructures ;

3° La longueur des enregistrements peut être fixe ou variable, avec ou sans séparateur de zone ;

4° Le caractère séparateur de zone éventuellement utilisé est unique et non équivoque dans chaque fichier.

II.-Chaque fichier remis est obligatoirement accompagné d'une description, qui précise :

1° Le nom, la nature et la signification de chaque zone ;

2° La signification des codes utilisés comme valeurs de zone ;

3° Toutes les informations techniques nécessaires au traitement des fichiers, et notamment le jeu de caractères utilisé, le type de structure, la longueur des enregistrements, les caractères séparateur de zone et séparateur d'enregistrement.

III.-Le codage des informations doit être conforme aux spécifications suivantes :

1° Les caractères utilisés appartiennent à l'un des jeux de caractères ASCII, norme ISO 8859-15 ou EBCDIC ;

2° Les valeurs numériques sont exprimées en mode caractère et en base décimale, cadrées à droite et complétées à gauche par des zéros pour les zones de longueur fixe. Le signe est indiqué par le premier caractère à partir de la gauche. La virgule sépare la fraction entière de la partie décimale. Aucun séparateur de millier n'est accepté ;

3° Les zones alphanumériques sont cadrées à gauche et complétées à droite par des espaces ;

4° Les dates sont exprimées au format AAAAMMJJ sans séparateur. Les heures sont exprimées au format HH : MM : SS.

IV.-En accord avec le service vérificateur, d'autres solutions d'échange peuvent être retenues dans la mesure où elles sont de nature à faciliter le traitement des données transmises.

V.-Les copies de fichiers sont remises sur des disques optiques de type CD ou DVD non réinscriptibles, clôturés de telle sorte qu'ils ne puissent plus recevoir de données et utilisant le système de fichiers UDF et/ ou ISO 9660.

En accord avec le service vérificateur, d'autre supports pourront être utilisés.

VI.-Les copies des fichiers mentionnées au I de l'article L. 47 A sont transmises, au choix du contribuable sous forme de :

1° Fichiers à plat, à organisation séquentielle et structure zonée remplissant les critères suivants :

a. Les enregistrements sont séparés par le caractère de contrôle Retour chariot et/ ou Fin de ligne ;

b. La longueur des enregistrements peut être fixe ou variable ;

c. Les zones sont obligatoirement séparées par une tabulation ou le caractère " | " ;

2° Fichiers structurés, codés en XML, respectant la structure du fichier XSD dont les spécifications sont consultables sur internet sur le site public  http :// www. impots. gouv. fr/.

VII.-1° Conformément au premier alinéa du I de l'article L. 47 A, l'ensemble des données comptables et des écritures retracées dans tous les journaux comptables au titre d'un exercice est remis dans un fichier unique, dénommé fichier des écritures comptables, dans lequel les écritures sont classées par ordre chronologique de validation. Ce fichier est constitué des écritures après opérations d'inventaire, hors écritures de centralisation et hors écritures de solde des comptes de charges et de produits. Il comprend les écritures de reprise des soldes de l'exercice antérieur et contient, pour chaque écriture, l'ensemble des données comptables figurant dans le système informatisé comptable de l'entreprise, les dix-huit premières informations devant obligatoirement correspondre, dans l'ordre, à celles listées dans le tableau suivant :

<table>
<tbody>
<tr>
<th>INFORMATION <br/>
</th>
<th>NOM DU CHAMP <br/>
</th>
<th>TYPE DE CHAMP <br/>
</th>
</tr>
<tr>
<td align="center">1. Le code journal de l'écriture comptable <br/>
</td>
<td align="center">JournalCode <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">2. Le libellé journal de l'écriture comptable <br/>
</td>
<td align="center">JournalLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">3. Le numéro sur une séquence continue de l'écriture comptable <br/>
</td>
<td align="center">EcritureNum <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">4. La date de comptabilisation de l'écriture comptable <br/>
</td>
<td align="center">EcritureDate <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">5. Le numéro de compte, dont les trois premiers caractères doivent correspondre à des chiffres respectant les normes du plan comptable français <br/>
</td>
<td align="center">CompteNum <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">6. Le libellé de compte, conformément à la nomenclature du plan comptable français <br/>
</td>
<td align="center">CompteLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">7. Le numéro de compte auxiliaire (à blanc si non utilisé) <br/>
</td>
<td align="center">CompAuxNum <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">8. Le libellé de compte auxiliaire (à blanc si non utilisé) <br/>
</td>
<td align="center">CompAuxLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">9. La référence de la pièce justificative <br/>
</td>
<td align="center">PieceRef <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">10. La date de la pièce justificative <br/>
</td>
<td align="center">PieceDate <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">11. Le libellé de l'écriture comptable <br/>
</td>
<td align="center">EcritureLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">12. Le montant au débit <br/>
</td>
<td align="center">Debit <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">13. Le montant au crédit <br/>
</td>
<td align="center">Credit <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">14. Le lettrage de l'écriture comptable (à blanc si non utilisé) <br/>
</td>
<td align="center">EcritureLet <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">15. La date de lettrage (à blanc si non utilisé) <br/>
</td>
<td align="center">DateLet <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">16. La date de validation de l'écriture comptable <br/>
</td>
<td align="center">ValidDate <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">17. Le montant en devise (à blanc si non utilisé) <br/>
</td>
<td align="center">Montantdevise <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">18. L'identifiant de la devise (à blanc si non utilisé) <br/>
</td>
<td align="center">Idevise <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
</tbody>
</table>

2° Si les informations " débit " et " crédit " ne sont pas présentes dans le système informatisé comptable de l'entreprise, les informations 12 et 13 peuvent être respectivement remplacées par " montant " et " sens ", sur le modèle suivant :

<table>
<tbody>
<tr>
<th>INFORMATION <br/>
</th>
<th>NOM DU CHAMP <br/>
</th>
<th>TYPE DE CHAMP <br/>
</th>
</tr>
<tr>
<td align="center">12. Le montant <br/>
</td>
<td align="center">Montant <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">13. Le sens <br/>
</td>
<td align="center">Sens <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
</tbody>
</table>

3° Pour chaque exercice, les premiers numéros d'écritures comptables du fichier correspondent aux écritures de reprise des soldes de l'exercice antérieur ;

4° Pour les fichiers à plat, la première ligne du fichier comporte le nom des champs, comme défini dans le tableau mentionné au 1° ou 2°.

VIII.-1° Conformément au deuxième alinéa du I de l'article L. 47 A, l'ensemble des données comptables et des écritures retracées dans tous les journaux comptables au titre d'un exercice est remis dans un fichier unique, dénommé fichier des écritures comptables, dans lequel les écritures sont classées par ordre chronologique de validation. Ce fichier est constitué des écritures après opérations d'inventaire, hors écritures de centralisation et hors écritures de solde des comptes de charges et de produits. Il comprend les écritures de reprise des soldes de l'exercice antérieur ;

2° Pour chaque exercice, les premiers numéros d'écriture comptable du fichier correspondent aux écritures de reprise des soldes de l'exercice antérieur ;

3° Lorsque le contribuable, imposable à l'impôt sur le revenu dans la catégorie des bénéfices non commerciaux ou dans celle des bénéfices agricoles, tient une comptabilité selon les règles du droit commercial, le fichier des écritures comptables contient, pour chaque écriture, l'ensemble des données comptables figurant dans le système informatisé comptable de l'entreprise, les dix-huit premières informations devant obligatoirement correspondre, dans l'ordre, à celles listées dans le tableau suivant :

<table>
<tbody>
<tr>
<th>INFORMATION <br/>
</th>
<th>NOM DU CHAMP <br/>
</th>
<th>TYPE DE CHAMP <br/>
</th>
</tr>
<tr>
<td align="center">1. Le code journal de l'écriture comptable (à blanc si non utilisé) <br/>
</td>
<td align="center">JournalCode <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">2. Le libellé journal de l'écriture comptable (à blanc si non utilisé) <br/>
</td>
<td align="center">JournalLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">3. Le numéro sur une séquence continue de l'écriture comptable <br/>
</td>
<td align="center">EcritureNum <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">4. La date de comptabilisation de l'écriture comptable <br/>
</td>
<td align="center">EcritureDate <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">5. Le numéro de compte (à blanc si non utilisé) <br/>
</td>
<td align="center">CompteNum <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">6. Le libellé de compte <br/>
</td>
<td align="center">CompteLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">7. Le numéro de compte auxiliaire (à blanc si non utilisé) <br/>
</td>
<td align="center">CompAuxNum <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">8. Le libellé de compte auxiliaire (à blanc si non utilisé) <br/>
</td>
<td align="center">CompAuxLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">9. La référence de la pièce justificative <br/>
</td>
<td align="center">PieceRef <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">10. La date de la pièce justificative <br/>
</td>
<td align="center">PieceDate <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">11. Le libellé de l'écriture comptable <br/>
</td>
<td align="center">EcritureLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">12. Le montant au débit <br/>
</td>
<td align="center">Debit <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">13. Le montant au crédit <br/>
</td>
<td align="center">Credit <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">14. Le lettrage de l'écriture (à blanc si non utilisé) <br/>
</td>
<td align="center">EcritureLet <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">15. La date de lettrage (à blanc si non utilisé) <br/>
</td>
<td align="center">DateLet <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">16. La date de validation de l'écriture comptable <br/>
</td>
<td align="center">ValidDate <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">17. Le montant en devise (à blanc si non utilisé) <br/>
</td>
<td align="center">Montantdevise <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">18. L'identifiant de la devise (à blanc si non utilisé) <br/>
</td>
<td align="center">Idevise <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
</tbody>
</table>

4° Si les informations " débit " et " crédit " ne sont pas présentes dans le système informatisé comptable de l'entreprise, les informations 12 et 13 peuvent être respectivement remplacées par " montant " et " sens ", sur le modèle suivant :

<table>
<tbody>
<tr>
<th>INFORMATION <br/>
</th>
<th>NOM DU CHAMP <br/>
</th>
<th>TYPE DE CHAMP <br/>
</th>
</tr>
<tr>
<td align="center">12. Le montant <br/>
</td>
<td align="center">Montant <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">13. Le sens <br/>
</td>
<td align="center">Sens <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
</tbody>
</table>

5° Lorsque le contribuable, imposable à l'impôt sur le revenu dans la catégorie des bénéfices agricoles, tient une comptabilité de trésorerie retraçant les recettes et les dépenses professionnelles, le fichier des écritures comptables contient, pour chaque écriture, l'ensemble des données comptables figurant dans le système informatisé comptable de l'entreprise, les vingt et une premières informations devant obligatoirement correspondre, dans l'ordre, à celles listées dans le tableau suivant :

<table>
<tbody>
<tr>
<th>INFORMATION <br/>
</th>
<th>NOM DU CHAMP <br/>
</th>
<th>TYPE DE CHAMP <br/>
</th>
</tr>
<tr>
<td align="center">1. Le code journal de l'écriture comptable (à blanc si non utilisé) <br/>
</td>
<td align="center">JournalCode <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">2. Le libellé journal de l'écriture comptable (à blanc si non utilisé) <br/>
</td>
<td align="center">JournalLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">3. Le numéro sur une séquence continue de l'écriture comptable <br/>
</td>
<td align="center">EcritureNum <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">4. La date de comptabilisation de l'écriture comptable <br/>
</td>
<td align="center">EcritureDate <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">5. Le numéro de compte (à blanc si non utilisé) <br/>
</td>
<td align="center">CompteNum <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">6. Le libellé de compte <br/>
</td>
<td align="center">CompteLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">7. Le numéro de compte auxiliaire (à blanc si non utilisé) <br/>
</td>
<td align="center">CompAuxNum <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">8. Le libellé de compte auxiliaire (à blanc si non utilisé) <br/>
</td>
<td align="center">CompAuxLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">9. La référence de la pièce justificative <br/>
</td>
<td align="center">PieceRef <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">10. La date de la pièce justificative <br/>
</td>
<td align="center">PieceDate <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">11. Le libellé de l'écriture comptable <br/>
</td>
<td align="center">EcritureLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">12. Le montant au débit <br/>
</td>
<td align="center">Debit <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">13. Le montant au crédit <br/>
</td>
<td align="center">Credit <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">14. Le lettrage de l'écriture (à blanc si non utilisé) <br/>
</td>
<td align="center">EcritureLet <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">15. La date de lettrage (à blanc si non utilisé) <br/>
</td>
<td align="center">DateLet <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">16. La date de validation de l'écriture comptable <br/>
</td>
<td align="center">ValidDate <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">17. Le montant en devise (à blanc si non utilisé) <br/>
</td>
<td align="center">Montantdevise <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">18. L'identifiant de la devise (à blanc si non utilisé) <br/>
</td>
<td align="center">Idevise <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">19. La date de règlement <br/>
</td>
<td align="center">DateRglt <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">20. Le mode de règlement <br/>
</td>
<td align="center">ModeRglt <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">21. La nature de l'opération (à blanc si non utilisé) <br/>
</td>
<td align="center">NatOp <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
</tbody>
</table>

6° Si les informations " débit " et " crédit " ne sont pas présentes dans le système informatisé comptable de l'entreprise, les informations 12 et 13 peuvent être respectivement remplacées par " montant " et " sens ", sur le modèle suivant :

<table>
<tbody>
<tr>
<th>INFORMATION <br/>
</th>
<th>NOM DU CHAMP <br/>
</th>
<th>TYPE DE CHAMP <br/>
</th>
</tr>
<tr>
<td align="center">12. Le montant <br/>
</td>
<td align="center">Montant <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">13. Le sens <br/>
</td>
<td align="center">Sens <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
</tbody>
</table>

7° Lorsque le contribuable, imposable à l'impôt sur le revenu dans la catégorie des bénéfices non commerciaux, tient une comptabilité de trésorerie retraçant les recettes et les dépenses professionnelles, le fichier des écritures comptables contient, pour chaque écriture, l'ensemble des données comptables figurant dans le système informatisé comptable de l'entreprise, les vingt-deux premières informations devant obligatoirement correspondre, dans l'ordre, à celles listées dans le tableau suivant :

<table>
<tbody>
<tr>
<th>INFORMATION <br/>
</th>
<th>NOM DU CHAMP <br/>
</th>
<th>TYPE DE CHAMP <br/>
</th>
</tr>
<tr>
<td align="center">1. Le code journal de l'écriture comptable (à blanc si non utilisé) <br/>
</td>
<td align="center">JournalCode <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">2. Le libellé journal de l'écriture comptable (à blanc si non utilisé) <br/>
</td>
<td align="center">JournalLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">3. Le numéro sur une séquence continue de l'écriture comptable <br/>
</td>
<td align="center">EcritureNum <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">4. La date de comptabilisation de l'écriture comptable <br/>
</td>
<td align="center">EcritureDate <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">5. Le numéro de compte (à blanc si non utilisé) <br/>
</td>
<td align="center">CompteNum <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">6. Le libellé de compte <br/>
</td>
<td align="center">CompteLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">7. Le numéro de compte auxiliaire (à blanc si non utilisé) <br/>
</td>
<td align="center">CompAuxNum <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">8. Le libellé de compte auxiliaire (à blanc si non utilisé) <br/>
</td>
<td align="center">CompAuxLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">9. La référence de la pièce justificative <br/>
</td>
<td align="center">PieceRef <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">10. La date de la pièce justificative <br/>
</td>
<td align="center">PieceDate <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">11. Le libellé de l'écriture comptable <br/>
</td>
<td align="center">EcritureLib <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">12. Le montant au débit <br/>
</td>
<td align="center">Debit <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">13. Le montant au crédit <br/>
</td>
<td align="center">Crédit <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">14. Le lettrage de l'écriture (à blanc si non utilisé) <br/>
</td>
<td align="center">EcritureLet <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">15. La date de lettrage (à blanc si non utilisé) <br/>
</td>
<td align="center">DateLet <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">16. La date de validation de l'écriture comptable <br/>
</td>
<td align="center">ValidDate <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">17. Le montant en devise (à blanc si non utilisé) <br/>
</td>
<td align="center">Montantdevise <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">18. L'identifiant de la devise (à blanc si non utilisé) <br/>
</td>
<td align="center">Idevise <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">19. La date de règlement <br/>
</td>
<td align="center">DateRglt <br/>
</td>
<td align="center">Date <br/>
</td>
</tr>
<tr>
<td align="center">20. Le mode de règlement <br/>
</td>
<td align="center">ModeRglt <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">21. La nature de l'opération (à blanc si non utilisé) <br/>
</td>
<td align="center">NatOp <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
<tr>
<td align="center">22. L'identification du client (à blanc si non utilisé) <br/>
</td>
<td align="center">IdClient <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
</tbody>
</table>

8° Si les informations " débit " et " crédit " ne sont pas présentes dans le système informatisé comptable de l'entreprise, les informations 12 et 13 peuvent être respectivement remplacées par " montant " et " sens ", sur le modèle suivant :

<table>
<tbody>
<tr>
<th>INFORMATION <br/>
</th>
<th>NOM DU CHAMP <br/>
</th>
<th>TYPE DE CHAMP <br/>
</th>
</tr>
<tr>
<td align="center">12. Le montant <br/>
</td>
<td align="center">Montant <br/>
</td>
<td align="center">Numérique <br/>
</td>
</tr>
<tr>
<td align="center">13. Le sens <br/>
</td>
<td align="center">Sens <br/>
</td>
<td align="center">Alphanumérique <br/>
</td>
</tr>
</tbody>
</table>

9° Pour les fichiers à plat, la première ligne du fichier comporte le nom des champs, comme défini dans les tableaux mentionnés aux 3° à 8°.

IX.-Le fichier des écritures comptables est nommé selon la nomenclature suivante :

SirenFECAAAAMMJJ, où " Siren " est le Siren du contribuable mentionné à l'article L. 47 A et AAAAMMJJ la date de clôture de l'exercice comptable.

X.-Les fichiers comprenant l'information 13 " Sens " doivent obligatoirement répondre à l'une des deux conditions suivantes :

1° la valeur " D " indique un montant au débit, la valeur " C " indique un montant au crédit ;

2° la valeur " + 1 " indique un montant au débit, la valeur "-1 " indique un montant au crédit.

Lorsque les valeurs utilisées sont " + 1/-1 ", il est impératif que celles-ci soient enregistrées sans espace entre les deux caractères, c'est-à-dire entre le " + ou-" et le " 1 ".

XI.-Chaque fichier remis est accompagné d'une description, qui précise :

1° Le nom, la nature et la signification de chaque zone ;

2° La signification des codes utilisés comme valeurs de zone ;

3° Toutes les informations techniques nécessaires à l'exploitation des fichiers, et notamment le jeu de caractères utilisés, le type de structure, la longueur des enregistrements.

XII.-Le codage des informations doit être conforme aux spécifications suivantes :

1° Les caractères utilisés appartiennent à l'un des jeux de caractères ASCII, norme ISO 8859-15 ou jeu de caractères unicode, norme ISO/ CEI 10646, de type UTF-8 ;

2° Les valeurs numériques sont exprimées en mode caractère et en base décimale, cadrées à droite et complétées à gauche par des zéros pour les zones de longueur fixe. La virgule sépare la fraction entière de la partie décimale. Aucun séparateur de millier n'est accepté. Les valeurs numériques peuvent être signées. Le signe est indiqué soit par le premier caractère à partir de la gauche, soit par le dernier caractère figurant à droite de la partie décimale ;

3° Les zones alphanumériques sont cadrées à gauche et complétées à droite par des espaces pour les zones de longueur fixe ;

4° Les dates sont exprimées au format AAAAMMJJ sans séparateur.

XIII.-Les copies des fichiers des écritures comptables sont remises selon les modalités définies en accord avec le service vérificateur.

Par dérogation au 1° des VII et VIII et en accord avec le service vérificateur, lorsque la volumétrie des données est trop élevée, le fichier peut être scindé en plusieurs parties.

Dans ce cas, tous les fichiers respectent le format et les normes définis par le présent article et sont remis simultanément. De plus, pour les fichiers à plat, tous les fichiers comportent sur la première ligne d'enregistrement le nom des champs définis dans le présent article.

XIV.-1° Par dérogation au 1° des VII et VIII, le service vérificateur peut demander que les contribuables mentionnés au 2° remettent plusieurs fichiers des écritures comptables. Le premier fichier est constitué des écritures centralisées et le ou les suivants des écritures détaillées correspondantes.

Dans ce cas, les fichiers précités respectent le format et les normes définis par le présent article. De plus, pour les fichiers à plat, les fichiers précités comportent sur la première ligne d'enregistrement le nom des champs définis dans le présent article ;

2° Le 1° s'applique aux contribuables autres que ceux soumis au régime défini à l'article 50-0 du code général des impôts lorsque leur chiffre d'affaires de l'exercice excède 152,4 millions d'euros, s'il s'agit d'entreprises dont le commerce principal est de vendre des marchandises, objets, fournitures et denrées à emporter ou à consommer sur place ou de fournir le logement, ou 76,2 millions d'euros, s'il s'agit d'autres entreprises.

Il s'applique également aux contribuables mentionnés à l'article L. 13 AA.
