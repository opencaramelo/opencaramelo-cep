# 🇧🇷OpenCaramelo-CEP
### WebService para consulta de CEP com dados totalmente publico, mais de 1.500.000 registros!

🔗 **Acesse o projeto online:** [https://www.opencaramelo.com](https://www.opencaramelo.com)

Uma **API** feita para **ajudar a comunidade de desenvolvedores** a integrar dados referente de CEP de forma rápida e prática.  
Pode ser usado em **qualquer projeto ou aplicação que precise informações de CEP de maneira simples e eficiente.**.

---

## 💡 Ideia do projeto

- **Consulta de CEP** de forma simples.
- Integração fácil com **qualquer sistema** que precise desses dados.
- **Limite de 100 requisições por minuto**, para uso consistente sem sobrecarregar o serviço.
- **100% gratuito**, permitindo que a comunidade participe, melhore e reutilize.

---

## 🔹 Como usar

Exemplo de requisição com `curl`:

```bash
curl https://mileena.opencaramelo.com/cep/74635055
```

```json
{
    "success": true,
    "message": null,
    "data": {
        "cep": "74635055",
        "cepFormatado": "74635-055",
        "uf": "GO",
        "nomeLocalidade": "Goiânia",
        "nomeBairro": "Setor Leste Vila Nova",
        "tipoLogradouro": "Rua",
        "nomeLogradouro": 208,
        "complementoLogradouro": null,
        "unidade": "",
        "codigoIbge": "5208707",
    }
}
```

## 🧭 Histórico de Versões

### 🧩 **v1.0.0 — Lançamento inicial**
- Implementação da **consulta de CEP individual**.  
- Retorno em **JSON estruturado** com campos completos (UF, cidade, bairro, logradouro, IBGE etc).  
- **API pública e gratuita**, sem necessidade de autenticação.  
- Limite de **100 requisições por minuto** por IP.

---

### 🔧 **Em desenvolvimento**
Atualmente está sendo desenvolvido um novo processo de **integração entre a base de CEPs e os dados oficiais do IBGE**.  
Essa etapa envolve:

- 🗂️ Criação de uma **base unificada de localidades** (municípios, distritos e sub-regiões).  
- 🔗 **Cruzamento entre CEPs e códigos IBGE**, garantindo maior precisão nas consultas.  
- 🧭 Implementação de **geolocalização (latitude e longitude)** para cada CEP.  
- ⚙️ Otimização da estrutura de dados para permitir **consultas mais rápidas e completas**. 

---
---
---

### E estão sempre atualizados?

Nos esforçamos para manter tudo atualizado, com revisões mensais sempre que possível.

### Encontrou algum problema?

Abra uma **issue** no GitHub e nos avise. Vamos adorar corrigir!

### 💡 Tem sugestões ou ideias?

Mande um chamado ou crie uma issue — seu feedback ajuda muito a melhorar o Opencaramelo-cep!

### 🍺 Quer apoiar o projeto?

Dar um ⭐ no GitHub ou contribuir ajuda a manter o Opencaramelo ativo e disponível para a comunidade.

Obrigado pelo apoio! 🙌

### Quer apoiar ainda mais o projeto?

Se o Opencaramelo-cep está sendo útil para você e **quiser me pagar uma cerveja 🍺**, você pode contribuir clicando aqui:

### Não é obrigatório, mas qualquer ajuda mantém o projeto ativo e disponível para a comunidade!  
### Também vale dar um ⭐ no GitHub 😉