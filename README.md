# AC-UPC

x86 Assembly un llarg trajecte per entendre-ho.

### Builing NASM with Xcode:

Per evitar rebre errors de sintaxi del Clang sobre tokens invàlids del ```.s```, cal:

Sempre ∀ .xcodeproj afegir a Target(M)->Build Rules->Filter: ```Copy to Target``` Nasm assembly file 

### Build script:
```julia
  /usr/local/bin/nasm -f macho64 ${INPUT_FILE_PATH} -o ${SCRIPT_OUTPUT_FILE_0}
```
### Output Files:
```julia
  $(DERIVED_FILE_DIR)/${INPUT_FILE_BASE}.o
```  
