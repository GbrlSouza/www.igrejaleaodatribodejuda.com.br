```
www.igrejaleaodatribodejuda.com.br/
│
├── assets/                    # Arquivos estáticos (CSS, JS, imagens, etc)
│   ├── css/
│   │   ├── bootstrap.min.css  # Bootstrap CSS
│   │   └── style.css          # Customizações de estilo
│   ├── js/
│   │   ├── bootstrap.min.js   # Bootstrap JS
│   │   └── main.js            # Scripts customizados
│   ├── img/
│       └── logo.png           # Logotipo da igreja
│
├── includes/                  # Partes reutilizáveis (header, footer, conexão com DB)
│   ├── header.php             # Cabeçalho do site (menu de navegação, etc)
│   ├── footer.php             # Rodapé do site
│   └── db.php                 # Conexão com banco de dados
│
├── admin/                     # Painel Administrativo
│   ├── index.php              # Página inicial do painel (dashboard)
│   ├── login.php              # Página de login do admin
│   ├── sermoes.php            # Gerenciamento de sermões
│   ├── eventos.php            # Gerenciamento de eventos
│   └── doacoes.php            # Relatórios de doações
│
├── page/                      # Páginas principais do site
│   ├── home.php               # Página inicial
│   ├── sobre.php              # Página "Quem Somos"
│   ├── cultos.php             # Página de cultos
│   ├── eventos.php            # Página de eventos
│   ├── sermoes.php            # Página de sermões gravados
│   ├── contato.php            # Página de contato
│   └── doacoes.php            # Página de doações
│
├── .htaccess                  # Arquivo de configuração do Apache
├── config.php                 # Configurações gerais do site
├── index.php                  # Arquivo de entrada principal
└── README.md                  # Descrição do projeto
