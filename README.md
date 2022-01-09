# Cas-kaggle
## Introducció
L'objectiu d'aquesta pràctica és aplicar tots els coneixements adquirits en l'assignatura impartida d'aprenentatge computacional en l'anàlisi d'un dataset determinat (en el meu cas en el dataset de churn_risk_score). S'han utilitzat múltiples llibreries, com pandas, sklearn, numpy, seaborn...

## Dataset
Tal i com ja s'ha comentat, he utilitzat el dataset de Churn Risk Score (el link per descargar-se el dataset és el següent: https://www.kaggle.com/imsparsh/churn-risk-rate-hackerearth-ml).

Cap empresa pot prosperar sense els clients; per tant, com més clients abandonin el negoci, pitjor és el futur d'aquest. De fet, una de les mètriques clau per mesurar l'èxit d'una empresa és mesurar la seva taxa de rotació de clients: com més baix sigui, més estimada serà l'empresa. Així doncs, segons el nostre dataset, com més clients tinguin un valor baix de churn_risk_score, millor anirà l'empresa.

L'objectiu és predir la puntuació del risc d'abandonament per a un lloc web basat en el conjunt de dades. Els valors de la puntuació són entre 1 i 5.

Les columnes són: customer_id, Name, age, gender, security_no, region_category, membership_category, joining_date, joined_through_referral, referral_id, preferred_offer_types, medium_of_operation, internet_option, last_visit_time, days_since_last_login, avg_time_spent, avg_transaction_value, avg_frequency_login_days, points_in_wallet, used_special_discount, offer_application_preference, past_complaint, complaint_status, feedback, churn_risk_score

El dataset consta de dos fixers, un és per entrenar els classificadors (train.csv) i l'altre és per predir el churn_risk_score (test.csv).
