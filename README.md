Per le librerie leggere usare file requirment.txt

For libraries information read file requirment.txt

Questo progetto è stato ideato per mostrare le mie compenze nella valutazione di un dataset seguendo le procedure tipiche di un analisi dati ordinaria, ovvero:
- Caricamento dei dati
- Pulizia e trattazione dei dati
- Analisi descrittiva
- Visualizzazione dei dati
- Elaborazione di conclusioni

Il dataset che è stato utilizzato è stato scaricato dal sito Keggle.com in formato .csv per una analisi locale. Il dataset è composto da dati generati per andare a valutare la presenza di metalli pesanti all'interno del suolo in una determinata area. Il dataset non mostava valori mancanti, così ho deciso di andare ad inserirli volontariamente all'interno del dataset per poter mostrare come questi debbano essere trattati.

I metodi principali che sono stati impigati per svolgere questa analisi dati sono stati la manipolazione del dataset attraverso le funzioni fornite dalle librerie Pandas e Numpy, unite alla potente creazione di grafici con le librerie Matplotlib e Seaborn. Per creare la distribuzione dei metallis sulle griglie è stato usata una libreria per svolgere operazioni quali interpolazioni e fitting chiamata Scipy.

I risultati principali di questa analisi sono che non vi è una correlazione evidente tra la presenza dei diversi metalli pesanti nel terreno e che la loro distribuzione nell'area sembra piuttosto omogenea senza punti di concentrazione rilevanti.
Un'altra informazione rilevante è quella ottenuta dalla media dei diversi valori dei metalli misurati nei campioni. Questo ci permette di fare un confronto con i limiti legislativi e verificare se possono esserci rischi per la salute in quest'area a causa della presenza di tali elementi.
I vari campioni sono stati singolarmente classificati sulla base di una valutazione complessiva dei singoli elementi ed è stato assegnato loro un livello di contaminazione. Ponendo su grafico a istogrammi queste classificazioni è possibile affermare che nel complesso il terreno può essere classificato come moderatamente inquinato.

------------------------------------------------------------------------------------------------------------------------------------------------------------

This project was designed to showcase my skills in evaluating a dataset by following the typical procedures of a standard data analysis, namely:

Data loading

Data cleaning and preprocessing

Descriptive analysis

Data visualization

Drawing conclusions

The dataset used was downloaded from Kaggle.com in .csv format for local analysis. It consists of generated data aimed at assessing the presence of heavy metals in the soil within a specific area. The dataset did not contain missing values, so I decided to intentionally insert some in order to demonstrate how they should be handled.

The main methods used to perform this data analysis included manipulating the dataset through functions provided by the Pandas and NumPy libraries, combined with the powerful plotting capabilities of Matplotlib and Seaborn. To create the distribution of metals across grids, a library for performing operations such as interpolation and fitting—Scipy—was used.

The main findings of this analysis show that there is no clear correlation between the presence of different heavy metals in the soil, and that their distribution across the area appears rather homogeneous without significant concentration points.
Another relevant insight comes from computing the average values of the metals measured in the samples. This allows us to compare them with legal thresholds and assess whether health risks might be present in the area due to these elements.

Each sample was individually classified based on an overall evaluation of the elements it contained, and a contamination level was assigned. By plotting these classifications in a histogram, it is possible to state that, overall, the soil can be classified as moderately polluted.