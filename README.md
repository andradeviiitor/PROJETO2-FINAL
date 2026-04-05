# PROJETO-2-FSDC


# Tema
- Barbearia Black Blade Barber

---

## Site
Dividido em 4 seções:

1. **Inicial**
   - Obj: dar boas vindas ao usuario e apresentar os diferenciais da barbearia

2. **Serviços**
   - Obj: citar alguns dos nosso serviços e preços

3. **Sobre**
   - Obj: contar um pouco sobre a historia da Black Blade Barber e seu compromisso com o cliente

4. **Agendamento**
   - Obj: formulario simples mas eficaz com nome, numero de telefone, tipo de corte e dia do corte

---

# Cores e Tipografia

## Tipografia
- playfair para titulos  
- josefin sans para descrições  

### Como usar fontes externas

1. encontre a fonte (use o google fonts)
2. pegue o Url
3. dentro do head use a tag:

```html
<link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
````

4. agora para usar a fonte é simples:

```css
h1 {
    font-family: 'Poppins', sans-serif;
    /* sempre após a fonte principal adicione um fallback */
}
```

---

### Vamos usar as fontes

**Playfair (url):**

```html
<link href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Playfair:ital,opsz,wght@0,5..1200,300..900;1,5..1200,300..900&display=swap" rel="stylesheet">
```

**Josefin Sans (url):**

```html
<link href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Josefin+Sans:ital,wght@0,100..700;1,100..700&family=Playfair:ital,opsz,wght@0,5..1200,300..900;1,5..1200,300..900&display=swap" rel="stylesheet">
```

---

## Cores da página

| Cor      | Função principal                 |
| -------- | -------------------------------- |
| Dourado  | Destaque / elementos importantes |
| Creme    | Texto principal                  |
| Escuro   | Fundo                            |
| Vermelho | Efeito visual / ambientação      |

---

🟡 **Dourados (destaque)**

```css
--gold1: #C9A84C;
--gold2: #E8C97A;
```

⚪ **Creme (texto principal)**

```css
--cream: #F2EAD8;
```

⚫ **Escuro (fundo)**

```css
--dark: #0D0B08;
```

🔴 **Vermelho escuro (efeito visual)**

```css
--red: #8B1A1A;
```

---

## Imagens de cada seção (para usar durante a produção)

<div style="text-align:center;">
  <img src="img/tela-inicial.png" width="500">
</div>

> O menu que está na parte superior de todas as telas deve conter position fixo ele pode ser copiado e obrigatorio em todos os codigos/branchs



<div style="text-align:center;">
  <img src="img/servicos.png" width="500">
</div>

<div style="text-align:center;">
  <img src="img/sobre.png" width="500">
</div>

<div style="text-align:center;">
  <img src="img/agendamento.png" width="500">
</div>

> Data de Entrega: 30/03/2026
