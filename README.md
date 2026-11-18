# Clínica Odonto+

Site demonstrativo de uma clínica odontológica. O visitante pode conhecer os serviços, consultar horários e acessar a opção de agendamento pelo WhatsApp. Os dados de contato e o número configurado são ilustrativos; a página não realiza agendamento real.

[Abrir a demonstração](https://raw.githack.com/sauloz20/clinica-odontologica/main/index.html) · [Ver o HTML](index.html)

![Página inicial no desktop e no celular com o menu aberto](docs/portfolio/responsividade.jpg)

## Tecnologias

HTML, CSS e JavaScript, com Bootstrap 5. O Bootstrap, a fonte Poppins e a imagem principal são carregados de serviços externos.

## Requisitos e execução

É necessário um navegador moderno. Para usar o comando abaixo, instale também Python 3 e Git. O carregamento dos recursos externos depende de internet.

```sh
git clone https://github.com/sauloz20/clinica-odontologica.git
cd clinica-odontologica
python -m http.server 8000
```

Abra [localhost:8000](http://localhost:8000). Como alternativa, sirva os arquivos por Apache/XAMPP.

## Navegação e contato

A classe `navbar-expand-lg` do Bootstrap mantém os links visíveis no desktop e os recolhe no celular. As âncoras levam a serviços, diferenciais, depoimentos e contato. Os botões montam links para o WhatsApp usando a constante `telefoneWhatsApp` no `index.html`; substitua o número ilustrativo antes de qualquer uso real.

## Estrutura

```text
index.html                     Conteúdo, navegação e ações do WhatsApp
style.css                      Estilos da página
docs/portfolio/responsividade.jpg  Imagem de demonstração
```
