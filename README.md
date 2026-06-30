SafetySentinel 🛡️
Automatizando a Inteligência em Inspeções de Segurança do Trabalho

🚀 O Projeto
O SafetySentinel é uma solução de engenharia de dados e IA desenvolvida para eliminar o gargalo operacional na gestão de inspeções industriais. O sistema processa automaticamente documentos não estruturados (PDFs de checklists de equipamentos), extrai informações cruciais por meio de OCR, classifica riscos baseados em regras de negócio e entrega um dashboard interativo para tomada de decisão ágil.

🛠️ Stack Tecnológica
Linguagem: Python 3.12

Engenharia de Dados: Pandas, Regex, OS (manipulação de arquivos).

IA/OCR: Pytesseract (Tesseract Engine) e pdf2image.

Interface: Streamlit (Dashboard analítico).

Infraestrutura: Google Colab (ambiente de processamento) e Google Drive (armazenamento).

⚙️ Arquitetura do Pipeline
O fluxo de dados foi desenhado para ser resiliente e automatizado:

Ingestão: Monitoramento automático de diretórios no Google Drive.

Processamento: Conversão de documentos escaneados (PDF/Imagem) para texto bruto.

Intelligence Layer: Extração de metadados via Regex e classificação de criticidade (Crítico, Médio, Baixo).

Visualização: Dashboard interativo em tempo real para monitoramento de conformidade.

📊 Visualização de Resultados
Abaixo, um exemplo da análise gerada pelo sistema:

(Aqui, você deve colar o print screen daquele gráfico de barras e da tabela que você gerou no Colab!)

🚀 Como Executar
Clone este repositório.

Configure o seu ambiente Google Colab com as dependências listadas no requirements.txt (ou instale via !pip install).

Adicione seus documentos de inspeção na pasta configurada no Drive.

Execute o pipeline de ingestão e visualize os resultados no dashboard.

📈 Roadmap de Evolução
[ ] Integração com LLMs (GPT-4 ou Llama 3) para análise semântica detalhada dos riscos.

[ ] Alertas automáticos via e-mail para riscos classificados como "Críticos".


Desenvolvido por Thiago Cassiano Gonçalves

[ ] Deploy do pipeline em arquitetura Serverless (AWS Lambda ou Google Cloud Functions).
