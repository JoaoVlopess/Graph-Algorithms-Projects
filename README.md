# 🐍 Python Data Structures & Concurrency Projects

Bem-vindo ao meu repositório de projetos focados em **estruturas de dados complexas** e **programação concorrente** utilizando Python.

Este *portfólio* contém implementações práticas de algoritmos de **Teoria dos Grafos** e soluções para problemas clássicos de **Sincronização de Threads**, desenvolvidos no ambiente **Google Colab** para experimentação.

---

## 🧭 Estrutura do Repositório

| Pasta/Arquivo | Descrição | Tópicos-Chave |
| :--- | :--- | :--- |
| `graphs/` | Implementação de algoritmos de busca e análise de conectividade em grafos (ex: topologia de redes). | **Teoria dos Grafos**, DFS (Recursiva e Iterativa), Análise de Redes, `networkx`. |
| `concurrency/` | Soluções para problemas de sincronização de processos e threads, prevenindo deadlock e starvation. | **Multithreading**, `threading.Lock`, Eventos (`threading.Event`), Deadlock, Starvation. |
| `*.ipynb` | Notebooks originais desenvolvidos no **Google Colab**. | **Python**, Ambientes de Notebook. |

---

## 💻 Destaques dos Projetos

### 1. 🌐 Algoritmos em Grafos

Projetos focados na manipulação e exploração de estruturas de dados de grafos.

* **Busca em Profundidade (DFS):** Implementação de uma **DFS** (recursiva e iterativa) para encontrar caminhos e verificar a conectividade em um grafo.
* **Análise de Conectividade:** Funções para determinar se uma rede (modelada como um grafo) está totalmente conectada.

### 2. 🚦 Concorrência e Sincronização

Implementação de soluções robustas para problemas de acesso concorrente a recursos.

* **O Jantar dos Filósofos (Solução com Coordenador):** Demonstração prática do uso de *threads* (`threading.Thread`) e mecanismos de sincronização (`Lock` e `Event`) para resolver um problema clássico de **deadlock** e **starvation**. A solução usa uma *thread* **Coordenadora** para garantir a justiça (*fairness*) e a alternância no uso dos recursos.

---

## 🛠️ Como Executar

Os projetos foram desenvolvidos para serem executados em **Python 3**.

1.  **Clone o Repositório:**
    ```bash
    git clone [URL_DO_SEU_REPOSITORIO]
    cd [NOME_DO_REPOSITORIO]
    ```
2.  **Abra os Notebooks:**
    Recomenda-se abrir os arquivos `.ipynb` diretamente no **Google Colab** para executar as células.
3.  **Dependências:**
    O módulo de grafos requer a biblioteca `networkx`:
    ```bash
    pip install networkx
    ```

---

## 🤝 Contribuições

Sinta-se à vontade para explorar, sugerir melhorias ou relatar problemas.
