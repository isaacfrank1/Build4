# Build4

crashes-joined.csv in Google sheets (has pivot table numbering crashes): https://docs.google.com/spreadsheets/d/1CMvPfTkIfLd13-pHrVYGGt8b8LB57R0kq6fbLLW_ask/edit#gid=54420065


Joining streets and crash data:
Drop crash data .csv into Mapshaper
Open console and type: -points x=Longtitude y=Latitude
<img width="1440" alt="Screen Shot 2023-04-06 at 12 34 35 PM" src="https://user-images.githubusercontent.com/128079269/230446118-aba31f97-5533-48c4-b194-aee5500c3154.png">
Drop street .geojson into Mapshaper
Open console and type: -join (filename) fields='corridor'
<img width="1440" alt="Screen Shot 2023-04-06 at 12 35 46 PM" src="https://user-images.githubusercontent.com/128079269/230446244-dbbe49aa-03fc-47b8-9511-453ab8b3417b.png">
