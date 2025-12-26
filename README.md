# Atividade TikTok

Atividade avaliativa de reprodução de UI Web a partir de imagem

## Sumário
1. [Objetivo](#objetivo)
2. [Protótipos](#protótipos)
3. [Checklist de Implementação](#checklist-de-implementação)
   - [Preparação](#preparação)
   - [Estrutura HTML](#estrutura-html)
   - [Estilização CSS3 Mobile First](#estilização-css3-mobile-first)
   - [Responsividade](#responsividade)
   - [Finalização](#finalização)

---

## Objetivo
Reproduzir a interface de usuário do TikTok utilizando HTML5 e CSS3 externo com abordagem mobile-first, baseando-se nos protótipos fornecidos.

## Protótipos
Os protótipos de referência estão disponíveis no diretório `prototipos/`:
- `tiktok-mobile.png` - [Design para dispositivos móveis](prototipos/tiktok-mobile.png)
- `tiktok-desktop.png` - [Design para desktop](prototipos/tiktok-desktop.png)

---

## Checklist de Implementação

---

### Preparação
- [x] Analisar os protótipos mobile e desktop
- [x] Identificar os componentes principais da interface
- [x] Planejar a estrutura semântica do HTML
- [x] Definir breakpoints para responsividade

---

### Estrutura HTML
- [x] Criar arquivo `index.html` na raiz do projeto
- [x] Configurar a estrutura básica HTML5:
  - [x] Adicionar `<!DOCTYPE html>`
  - [x] Configurar tag `<html>` com atributo `lang="pt-BR"`
  - [x] Criar seção `<head>` com:
    - [x] Meta charset UTF-8
    - [x] Meta viewport para responsividade
    - [x] Tag `<title>` apropriada
    - [x] Link para arquivo CSS externo
- [x] Estruturar o `<body>` com elementos semânticos:
  - [x] Header (cabeçalho/navegação)
  - [x] Main (conteúdo principal)
  - [x] Footer (rodapé)
- [x] Adicionar conteúdo textual e imagens conforme protótipo mobile

---

### Estilização CSS3 Mobile First
- [x] Criar arquivo `tiktok.css` (recomendado: criar pasta `css/` e salvar como `css/tiktok.css`)
- [x] Configurar reset/normalize CSS:
  - [x] Remover margens e paddings padrão
  - [x] Definir box-sizing como border-box
- [x] Implementar estilos base (mobile first):
  - [x] Tipografia (fontes, tamanhos, cores)
  - [x] Cores de fundo
  - [x] Espaçamentos (margins e paddings)
  - [x] Layout flexbox ou grid
- [x] Estilizar componentes específicos:
  - [x] Barra de navegação/header
  - [x] Cards ou seções de conteúdo
  - [x] Botões e elementos interativos
  - [x] Imagens e ícones
  - [x] Footer
- [x] Aplicar efeitos CSS3:
  - [x] Transições
  - [x] Sombras (box-shadow)
  - [x] Bordas arredondadas (border-radius)
  - [x] Gradientes (se aplicável)

---

### Responsividade
- [ ] Implementar media queries para tablet (min-width: 768px):
  - [ ] Ajustar layouts
  - [ ] Modificar tamanhos de fonte
  - [ ] Reorganizar elementos se necessário
- [ ] Implementar media queries para desktop (min-width: 1024px):
  - [ ] Aplicar layout do protótipo desktop
  - [ ] Ajustar larguras máximas
  - [ ] Otimizar espaçamentos
- [ ] Testar em diferentes tamanhos de tela (sugestão: 320px, 768px, 1024px, 1440px) usando DevTools do navegador

---

### Finalização
- [ ] Testar a página em navegadores diferentes (Chrome, Firefox, Safari, Edge), inclusive usando F12 para o mobile
- [ ] Verificar acessibilidade básica:
  - [ ] Alt text em imagens
  - [ ] Contraste de cores adequado
  - [ ] Estrutura de headings hierárquica
     
---

### Observações

- as imagens e artistas são da conta real do professor
- pode utilizar as mesmas imagens do protótipo ou pegar suas próprias imagens
- as imagens devem ser colocadas em uma pasta, sugestão `imagens`
- deve ter mais que 3 itens em cada _carousel_
- [ ] Documentar decisões técnicas (se necessário)
- [ ] Fazer commit final do projeto
