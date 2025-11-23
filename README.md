# API Java – CI/CD

Este projeto contém uma API Java com Maven que possui pipelines de **Integração Contínua (CI)** e **Entrega Contínua (CD)**

---

## 🚀 Estrutura da entrega


### ✔️ CI – Integração Contínua
A pipeline realiza automaticamente:

- Checkout do código  
- Configuração do Java 17  
- Build com Maven  
- Execução dos testes automatizados  


---

### ✔️ CD – Entrega Contínua
Sempre que houver push na branch, ocorre:

- Build da imagem Docker  
- Publicação no GitHub Container Registry (GHCR)  

