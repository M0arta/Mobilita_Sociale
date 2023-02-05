# Mobilita_Sociale

In questo progetto esploriamo lo stato dell'ascensore sociale italiano per diverse catergorie socio-economiche e demografiche in diverse regioni italiane.
Per farlo partiamo  dai microdati del questionario alle Famiglie Italiane della Banca d'Italia usando i dati 2020 e 1986 per identificare due generazioni di italiani
e poter osservare i pattern di mobilità tra categorie socioeconomiche. 


figli_2020.dta --> contiene i dati sulla popolazione 25-45 yo nel 2020 
genitori_1986.dta --> contiene i dati sulla popolazione 25-45 yo nel 1986
q20a.dta --> contiene informazioni addizionali su famiglia di origine dei figli rispondenti

#Variabili: 

son :  dummy 1 per i figli e 0 per i genitori
y : reddito netto annuo percepito 
quintile :  categorizzazione con rispetto della popolazione totale (non solo 25-45)
area 3 : divisione italia in tre grandi macro aree
area 5 : divisione Italia in 5 macro aree

Attualmente lavorando su: come assegnare i figli agli pseudo genitori


# Analisi in master_do_file


