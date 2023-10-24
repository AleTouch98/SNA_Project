# Football transfers dataset

This dataset includes transfers of the major European football leagues from 2009 to 2021:

- ENGLISH PREMIER LEAGUE
- LA LIGA
- SERIE A
- BUNDESLIGA
- FRENCH LIGUE 1
- LIGA PORTUGAL BWIN
- DUTCH EREDIVISIE

Dataset can be found in `dataset\transfers.csv` file.

## Variables

`league` - codename of the football league. Takes the following values:
- `GB1` ENGLISH PREMIER LEAGUE
- `ES1` LA LIGA
- `IT1` SERIE A
- `L1` BUNDESLIGA
- `FR1` FRENCH LIGUE 1
- `PO1` LIGA PORTUGAL BWIN
- `NL1` DUTCH EREDIVISIE
 
`season` -  La stagione a cui si riferisce il trasferimento.
`window` - La finestra di trasferimento, che può essere "s" (estate) o "w" (inverno).
`team_id` - L'ID della squadra utilizzato da Transfermarkt.
`team_name` - Il nome della squadra.
`team_country` - Il paese della squadra.
`dir` - La direzione del trasferimento, che può essere "in" (acquisto) o "left" (vendita).
`player_id` - L'ID del calciatore utilizzato da Transfermarkt.
`player_name` - Il nome del calciatore.
`player_age` - L'età del calciatore al momento del trasferimento.
`player_nation` - La nazionalità del calciatore.
`player_nation2` - La seconda nazionalità del calciatore, se presente.
`player_pos` - La posizione in campo del calciatore.
`counter_team_id` - L'ID della squadra controparte coinvolta nel trasferimento.
`counter_team_name` - Il nome della squadra controparte.
`counter_team_country` - Il paese della squadra controparte.
`transfer_fee_amnt` - L'importo del trasferimento in euro.
`market_val_amnt` - Il valore di mercato del calciatore in euro al momento del trasferimento, stimato da Transfermarkt.
`is_free` - Se si tratta di un trasferimento gratuito ("True" o "False").
`is_loan` - Se si tratta di un prestito ("True" o "False").
`is_loan_end` - Se si tratta della fine di un prestito ("True" o "False").
`is_retired` - Se il calciatore è ritirato ("True" o "False").
`transfer_id` - L'ID del trasferimento utilizzato da Transfermarkt.

## Data source and code
- Data was scraped from [Transfermarkt.com](https://www.transfermarkt.com). Raw data files can be found in `data` folder.
- Scraper and preprocessing Jupyther notebooks with code can be found in `src` folder.