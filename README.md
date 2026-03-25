# Computer vision — proposta técnica e comercial

Repositório com uma **proposta em página única** (HTML + CSS) para um **sistema de visão computacional** voltado a **controle de qualidade na produção de blocos de concreto**: classificação automática (boa / ruim / não identificada), registro histórico, dashboard, alertas via WhatsApp e rastreabilidade operacional.

O documento está em **português (pt-BR)** e foi pensado para leitura no navegador ou exportação para PDF (impressão).

## Conteúdo do arquivo

| Arquivo       | Descrição |
|---------------|-----------|
| `index.html`  | Proposta completa: capa, 15 seções numeradas, estilos embutidos (sem build nem dependências). |

### Seções principais (visão geral)

1. Visão geral e propósito  
2. Fluxo operacional (captura → IA → classificação → banco → alertas → relatórios)  
3. Escopo funcional  
4. Arquitetura (servidor local vs **AWS ECS/Fargate + agente local** — recomendada)  
5. Inteligência artificial (premissas, limites de precisão, pipeline de dados)  
6. Dependências e premissas do projeto  
7. Plano por fases (descoberta, MVP, dashboard/alertas, validação; suporte opcional)  
8. Limites de escopo, riscos e mitigações  
9. Valor gerado, cronograma e investimento  
10. Termos comerciais e próximos passos  

Valores, datas, referência do documento e placeholders (por exemplo nome do cliente) estão definidos **dentro do HTML** e podem ser ajustados diretamente no arquivo.

## Como visualizar

Abra `index.html` no navegador:

```bash
open index.html
```

Ou sirva a pasta com qualquer servidor HTTP estático, se preferir:

```bash
python3 -m http.server 8080
```

Depois acesse `http://localhost:8080/index.html`.

## Requisitos

Nenhum. Apenas um navegador moderno. As fontes são carregadas do [Google Fonts](https://fonts.google.com/) (requer acesso à internet na primeira carga, a menos que as fontes estejam em cache).

## Licença e confidencialidade

O texto da proposta trata o material como **confidencial** em relação ao cliente. Este repositório é o veículo do documento; defina licença e política de uso conforme a sua organização.
