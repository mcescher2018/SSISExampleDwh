# SSISExampleDwh
Soluzione con raccolta di package di esempio per alcuni task comuni in SSIS. 

Da aprire con Visual Studio 2019 (non compatibile con 2022).

Package

- BasicETL, caricamento di alcune tabelle da un DB a un DWH Locali
- Blobs, caricamento di un file in un campo blob di una tabella SQL Server del DWH
- CallAPI, chiamata ad una API da SSIS e esempio di script con codice C#
- ImportFromExcel, caricamento dati da Excel a tabella SQL Server 
- ExportToExcel, esportazione dati da tabella SQL server a file Excel

Note:

- verificare che i connection manager siano coerenti con le impostazioni del PC dove si installa (percorsi file, nome istanza sql...)
- attenzione all'export dei long text su Excel (vedi problema dell'inferenza del tipo dalle prime 8 righe)

