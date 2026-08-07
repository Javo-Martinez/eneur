/revista-flatfile
├── index.php                 # Hace el redirect dinámico al último número disponible
├── index-1.php               # Portada del Número 1 (Botón ENTRAR)
├── index-2.php               # Portada del Número 2 (Botón ENTRAR)
├── eneur.php                 # LA SPA CORE: Maneja el índice (id=0), las notas (id>=1) y el historial
├── /data
│   ├── /numero-1             # Carpeta exclusiva del Número 1
│   │   ├── info.json         # Tapa: datos del número, autor de la imagen, contratapa
│   │   ├── notas.json        # "La Base de Datos" de este número (Metadatos + Cuerpo)
│   │   └── secciones.json    # Índices cortos filtrados por sección
│   └── /paginas-fijas
│       ├── quienes-somos.json # Staff y lista de colaboradores
│       └── contacto.json      # Datos de contacto
└── /secciones                # Páginas independientes (Secciones, Contacto, etc.)
&#x20;   ├── quienes-somos.php     
&#x20;   ├── contacto.php          
&#x20;   └── contratapa.php      

