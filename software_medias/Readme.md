librerias: pandas y openpyxl y xlwings
El excel 1 lleva la barra para windows y el excel 2 la barra del 7 para linux
El medias_excel_1 lleva la barra para windows y el media excel 2 para linux
Para compilar:
pyinstaller --onefile --console --name Medias_Windows.exe --clean main.py 


## Notas:
- Liga_test_1 tiene barra de windows
- Liga_test_2 tiene barra de linux
- Los scripts de ptython: 1 Windows, 2 Linux, 3 Apple
- Se debe de indicar en el scrip de pyhton el arhivo de excel que se va a leer (1 o 2)

## Funcionamiento:
- Se abre el excel y se hacen los cambios de tiempos en las hojas de series
- Se guarda el excel
- Se ejecuta el programa que leera esas hojas y actualizara los csv
- Se actualizan los datos en el excel que leeran la solucion de los csv