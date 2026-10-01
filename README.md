# Calculadora de Retorno Real dos Imóveis

Ferramenta gratuita e prática pra o investidor imobiliário pessoa física descobrir o **retorno real de cada imóvel** — descontando IPTU, condomínio, vacância, reforma e IR, somando valorização — e comparar com o **CDI**.

**Roda 100% no seu navegador. Nenhum dado sai do seu computador.**

## Usar

- **Online (recomendado):** acesse a versão hospedada (GitHub Pages). Libera a **proteção por PIN** — seus dados ficam criptografados (AES-GCM, chave derivada do PIN) e ilegíveis sem ele.
- **Offline:** baixe o `index.html` e abra no navegador. Funciona igual, mas o PIN fica indisponível (o navegador só libera criptografia em contexto seguro `https`). Seus dados continuam só no seu navegador.

## O que calcula

- Retorno real líquido por imóvel e do portfólio inteiro, ao ano.
- Comparação com o CDI (barra vermelha quando o imóvel rende menos que a renda fixa).
- Considera IPTU, condomínio, vacância, reforma, IR sobre aluguel e valorização estimada.

## Privacidade

Tudo acontece no navegador (`localStorage`). Não há servidor, não há banco de dados, nada é enviado a lugar nenhum. Com um PIN, os dados salvos ficam criptografados.

## Aviso

Estimativa com base nos dados que você informar. Não é recomendação de investimento.

---

Feito por **André Modesti**. Licença MIT — use, adapte e distribua livremente.
