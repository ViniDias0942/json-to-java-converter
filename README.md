📡 **Projeto Java - Conversão JSON para Objetos Java com Gson**

🔖 **Sobre o projeto**  
Este projeto foi desenvolvido como um exercício prático para demonstrar diferentes formas de converter dados JSON em objetos Java utilizando a biblioteca Gson. Ele cobre cenários que vão desde a conversão simples até o tratamento de campos opcionais e objetos aninhados.

🎯 **Funcionalidades**  
✔️ Permite a conversão de JSON para objetos Java com:

- Campos completos e obrigatórios  
- Campos opcionais, suportando JSONs parciais  
- Estruturas aninhadas com objetos dentro de objetos  

🧠 **Técnicas e conceitos utilizados**  
✅ Uso da biblioteca Gson para serialização e desserialização JSON  
✅ Configurações flexíveis de parsing com `GsonBuilder` (`serializeNulls()`, `setLenient()`)  
✅ Uso de records do Java para definição simples e imutável de dados  
✅ Manipulação de JSON aninhado com objetos compostos (`Livro` e `Editora`)  

🚀 **Tecnologias e ferramentas**  
- Java 17+  
- IntelliJ IDEA
- Git e GitHub
- Biblioteca Gson (Google)  

📂 **Organização do Projeto**

```
src/
├── ConversaoJsonParaObjeto.java # Exemplo de conversão JSON completo para Pessoa
├── ConversaoFlexivel.java # Exemplo de conversão com campos opcionais
├── ConversaoAninhado.java # Exemplo com JSON aninhado: Livro e Editora
├── Pessoa.java # Record Pessoa
├── Livro.java # Record Livro
└── Editora.java # Record Editora
```

✍️ **Autor**  
Vinícius Alves Dias

Projeto desenvolvido para fins educacionais, com foco em manipulação e integração JSON em Java.
