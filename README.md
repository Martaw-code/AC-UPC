# AC-UPC

x86 Assembly un llarg trajecte per entendre-ho.

### Builing NASM with Xcode:

Primer de tot, cal instal·lar el paquet ```nasm``` amb la comanda: ```$ brew install nasm```

Seguidament, per evitar rebre errors de sintaxi del ```.s```, caldrà afegir ∀ ```.xcodeproj```:

<img width="861" alt="Captura de pantalla 2021-02-26 a las 18 14 39" src="https://user-images.githubusercontent.com/62546580/109332768-dd4cf800-785e-11eb-96e8-73878724277c.png">

### Build script:
```julia
  /usr/local/bin/nasm -f macho64 ${INPUT_FILE_PATH} -o ${SCRIPT_OUTPUT_FILE_0}
```
### Output Files:
```julia
  $(DERIVED_FILE_DIR)/${INPUT_FILE_BASE}.o
```  
