# 📁 Pasta de Imagens

Coloque suas fotos e imagens de projetos aqui.

## Foto de Perfil (Seção "Sobre")
- Nome sugerido: `profile.jpg` ou `minha-foto.jpg`
- Tamanho ideal: mínimo 600x750px, proporção 4:5
- Formatos aceitos: JPG, PNG, WebP

## Imagens dos Projetos
- Nome sugerido: `projeto-1.jpg`, `projeto-2.jpg`, `projeto-3.jpg`
- Tamanho ideal: 1280x720px (proporção 16:9)
- Formatos aceitos: JPG, PNG, WebP

---

## Como usar no index.html

### Para a foto de perfil:
Localize a seção `<!-- COMO ADICIONAR SUA FOTO -->` no index.html e:
1. Descomente a linha `<img src="assets/images/sua-foto.jpg" ...>`
2. Substitua `sua-foto.jpg` pelo nome real do arquivo
3. Delete o div `.about__photo-placeholder`

### Para imagens de projetos:
Localize os comentários `<!-- COMO ADICIONAR IMAGEM DO PROJETO -->` e:
1. Substitua o div `.project-card__thumb-placeholder` por:
   `<img src="assets/images/projeto-1.jpg" alt="Nome do seu projeto">`
