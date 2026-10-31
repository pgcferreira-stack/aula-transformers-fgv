# Transformers: do texto à imagem

Material hands-on da aula de NLP e IA generativa (MBA FGV).

## Como abrir os notebooks no Google Colab

1. Acesse [colab.research.google.com](https://colab.research.google.com) e entre com sua conta Google.
2. Na janela que abrir, clique na aba **GitHub**. Se a janela não abrir, vá em **Arquivo → Abrir notebook**.
3. Cole o endereço deste repositório (a URL desta página) e aperte Enter.
4. Clique no notebook da aula.
5. **Importante:** antes de mexer, vá em **Arquivo → Salvar uma cópia no Drive**. Sem isso, suas alterações se perdem.
6. Ligue a GPU: **Ambiente de execução → Alterar o tipo de ambiente de execução → GPU T4 → Salvar**.
7. Rode as células com **Shift + Enter**, de cima para baixo.

## Roteiro

Atalho: clique no botão **Open in Colab** do notebook. Depois siga os passos 5 a 7 acima.

| Notebook | Módulo | |
|---|---|---|
| `01_classificacao_ner` | Classificação de texto e NER: ML clássico × transformers | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pgcferreira-stack/aula-transformers-fgv/blob/main/notebooks/01_classificacao_ner.ipynb) |
| `02_atencao_e_minigpt` | Arquitetura do transformer e um mini-GPT treinado do zero | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pgcferreira-stack/aula-transformers-fgv/blob/main/notebooks/02_atencao_e_minigpt.ipynb) |
| `03_respostas_automaticas` | Fine-tuning (LoRA) × RAG para respostas automáticas | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pgcferreira-stack/aula-transformers-fgv/blob/main/notebooks/03_respostas_automaticas.ipynb) |
| `04_imagem` | Vision Transformer, Deep Dream e texto → imagem | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pgcferreira-stack/aula-transformers-fgv/blob/main/notebooks/04_imagem.ipynb) |
| `05_miniprojeto_texto_imagem` | Miniprojeto: DreamBooth + LoRA (entrega em 2 semanas) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pgcferreira-stack/aula-transformers-fgv/blob/main/notebooks/05_miniprojeto_texto_imagem.ipynb) |

As células marcadas com `# TODO` são para vocês completarem: troquem o `...` pelo código.

## Dados e modelos
- Reviews: [B2W-Reviews01](https://huggingface.co/datasets/ruanchaves/b2w-reviews01)
- *Dom Casmurro*, de Machado de Assis (Projeto Gutenberg, domínio público)
- `dados/faq_lojaaurora.jsonl`: FAQ de uma loja fictícia criado para a aula
- Modelos abertos do Hugging Face Hub. A licença de cada um está no *model card*.
