# Clínica Integris — novo site (prévia)

Site estático (HTML, CSS e JS puros). Não precisa de build.

## Publicar
1. Crie um repositório no GitHub e envie todos os arquivos desta pasta.
2. Na Vercel: Add New → Project → importe o repositório → Framework Preset: **Other** → Deploy.

## Fotos
Coloque as fotos em `assets/` com estes nomes (JPG, ~1600px no lado maior, comprimidas). Sem o arquivo, o site mostra o nome do arquivo no espaço.

| Arquivo | Onde aparece |
|---|---|
| hero-dra-amanda.jpg | Topo (retrato vertical) |
| caso1-antes.jpg / caso1-depois.jpg | Antes e depois — implante unitário |
| caso2-antes.jpg / caso2-depois.jpg | Antes e depois — implante múltiplo |
| caso3-antes.jpg / caso3-depois.jpg | Antes e depois — prótese protocolo |
| esp-implantes.jpg, esp-protese.jpg, esp-facetas.jpg, esp-clareamento.jpg, esp-ortodontia.jpg | Cards de especialidades |
| dra-amanda.jpg | Capa do vídeo de apresentação |
| consultorio.jpg | Seção "Por que a Integris" |

Antes e depois: só casos da própria clínica, com autorização do paciente.

## Pendências (procure por `[` no index.html e no llms.txt)
- Sobrenome da Dra. Amanda, CRO-CE, CRO da clínica (EPAO) e CNPJ.
- Texto de apresentação e formação da Dra. Amanda.

## Ao lançar no domínio oficial
- Remova `<meta name="robots" content="noindex, nofollow">` do index.html.
- Troque o conteúdo do robots.txt pelo indicado no próprio arquivo.
- Envie o sitemap no Google Search Console.
- Troque `og:image` por URL absoluta (https://clinicaintegris.com.br/assets/og-image.jpg).
