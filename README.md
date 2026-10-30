# IAQ Assessment Tool – V3

Neue Bereiche: **6 · Raumberichte** (je Raum Auswertung und HTML-Download) und **7 · Empfehlungen** (Gebäudeübersicht, Empfehlungen und HTML-Gesamtbericht). Das bisherige Export-Menü ist nun **8 · Export**.

Normgrenzwerte und Konformitätsbeurteilung sind noch **nicht** implementiert. Mittelwerte sind ungewichtet. Empfehlungen beschreiben Datenlücken, Repräsentativität und Dokumentation, keine gesundheitlichen Wirkungen.

## GitHub / Streamlit Cloud
Die bisherige `app.py` im GitHub-Repository durch die neue ersetzen und **Commit changes** wählen. `requirements.txt` kann unverändert bleiben, sofern Streamlit und pandas bereits installiert sind. Streamlit stellt die neue Version automatisch bereit.

## Lokaler Start
`python3 -m pip install -r requirements.txt`
`python3 -m streamlit run app.py`

Daten regelmässig über **8 · Export** als JSON sichern. HTML-Berichte im Browser öffnen und optional als PDF drucken.
