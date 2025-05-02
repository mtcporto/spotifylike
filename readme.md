# Bandas de João Pessoa - App Like Spotify

## Descrição

Uma aplicação web inspirada no Spotify para descobrir e reproduzir músicas de artistas paraibanos. O projeto apresenta bandas e artistas de João Pessoa, permitindo ouvir previews de músicas, visualizar álbuns e singles, e aprender mais sobre a cena musical local.

## Recursos

- **Interface inspirada no Spotify**: Design moderno e responsivo que lembra a plataforma Spotify
- **Visualização de artistas**: Cards interativos com imagens dos artistas locais
- **Reprodução de músicas**: Player integrado para reprodução de arquivos locais
- **Integração com Spotify**: Links para abrir músicas no Spotify quando não disponíveis localmente
- **Detalhes de álbuns**: Visualização de álbuns, singles e coletâneas de cada artista
- **Playlists**: Reprodução sequencial ou aleatória de músicas
- **Background animado**: Efeitos visuais dinâmicos no cabeçalho usando VANTA.js
- **Busca de artistas**: Pesquisa por nome de artistas locais

## Tecnologias Utilizadas

- **HTML5**: Estruturação semântica do conteúdo
- **CSS3**: Estilização avançada com variáveis CSS e flexbox
- **JavaScript**: Programação client-side para interatividade
- **Spotify Web API**: Integração para obtenção de metadados de artistas, álbuns e músicas
- **Bootstrap 4**: Framework CSS para layout responsivo
- **Font Awesome**: Biblioteca de ícones para interface
- **Web Audio API**: Reprodução e controle de áudio pelo navegador
- **VANTA.js**: Efeitos de background animados e interativos
- **Three.js**: Renderização WebGL (usado pelo VANTA.js)
- **Google Fonts**: Tipografia web com Montserrat e Open Sans
- **localStorage**: Armazenamento local para cache de dados dos artistas

## Arquitetura

A aplicação segue uma arquitetura modular baseada em componentes front-end:

- **Sistema de estado**: Gerenciamento centralizado do estado da aplicação (músicas, artista atual, modo shuffle)
- **Caching**: Armazenamento eficiente de dados de artistas para reduzir requisições à API
- **Gerenciamento de tokens**: Autenticação OAuth com o Spotify usando Client Credentials Flow
- **Tratamento de erros**: Sistema robusto para lidar com falhas de carregamento de imagens e dados

## Artistas Incluídos

- Chico Correa & Electronic Band (com arquivos locais)
- Tapuia
- Seu Pereira e Coletivo 401
- Lily
- Val Donato
- Furmiga Dub
- Pedro Faissal & o Meiofree
- E outros artistas paraibanos disponíveis via Spotify API

## Como Executar

1. Clone o repositório
2. Configure suas credenciais do Spotify API (Client ID e Client Secret)
3. Hospede os arquivos em um servidor web (como Apache ou Nginx)
4. Acesse o aplicativo através do navegador

## Requisitos

- Navegador web moderno com suporte a JavaScript ES6+
- Conexão com a internet para acessar a API do Spotify
- Credenciais de desenvolvedor do Spotify (para API)

## Limitações

- Reprodução local disponível apenas para arquivos incluídos no servidor
- Previews do Spotify requerem que o usuário tenha uma conta Spotify
- A API do Spotify tem limitações de taxa de requisições

## Melhorias Futuras

- Autenticação de usuários para acesso a mais recursos do Spotify
- Personalização de playlists
- Adição de mais artistas locais
- Sistema de recomendações baseado em gêneros musicais paraibanos

---

Desenvolvido como projeto de exemplo para demonstração de técnicas de desenvolvimento web front-end e integração com APIs de música.