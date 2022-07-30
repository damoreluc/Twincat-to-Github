# Istruzioni

1. su GitHub creare il nuovo repository **vuoto** col nome della soluzione TwinCAT, ad esempio _TwinCAT to Github_
2. sul pc locale, creare con Esplora Risorse una cartella per il progetto TwinCAT, ad esempio:<br>
   C:\Users\luca\Documents\Workspace\TwinCAT to Github
   
2. tramite Windows shell, creare in questa cartella il repository, che sarà inizialmente vuoto: <br>
   git init
   
3. avviare TwinCAT3 e creare la nuova soluzione **nel modo seguente** 
    1. Casella _Nome:_ digitare il nome della soluzione, ad esempio **TwinCAT to Github**
    2. Casella _Percorso:_ selezionare con *Sfoglia* il percorso della cartella creata al punto 2.
    3. **Togliere** la spunta dalle caselle: **Crea directory per soluzione** e da **Crea nuovo repository Git**
  
4. Da Esplora risorse, copiare il file .gitignore nella cartella creata al punto 2.
5. In TwinCAT3 creare il nodo di progetto del Codice PLC
6. In TwinCAT3 passare al **Team Explorer** e selezionare **Modifiche**, aggiungere allo stage tutti i file indicati come modificati (es. 7 file) ed eseguire il primo commit sul repository locale
7. In TwinCAT3 passare al **Team Explorer** e selezionare **Sincronizzazione**: qui viene proposta la selezione del servizio di repository remoto, **non usare** AzureDevOp, ma scegliere la seconda opzione GIT, inserire l'url del repository su GitHub creato al punto 1. e confermare
