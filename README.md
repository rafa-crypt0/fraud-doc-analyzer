# Fraud Document Analyzer (Offline Demo)

Pipeline offline para análise automatizada de documentos (PDF/Imagem) com foco em:

- Extração de texto (PDF digital ou OCR)
- Validação de CPF/CNPJ
- Detecção de padrões suspeitos (datas futuras, edição de valores)
- Score probabilístico de risco
- Relatório com mascaramento de dados sensíveis

## 🚀 Como usar (Colab)

1. Abra o notebook
2. Faça upload de um PDF ou imagem
3. Rode todas as células
4. Baixe:
   - report_masked.json
   - flags.csv

## 📂 Estrutura

- notebooks/ → notebook principal
- samples/ → documentos fake de teste
- outputs/ → relatórios (não versionados)

## 🔒 Segurança

- CPF/CNPJ são mascarados no output
- Não commitar documentos reais
- Projeto demonstrativo (offline)
