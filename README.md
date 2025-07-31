# 📡 Projeto Java - Conversão JSON para Objetos Java com Gson

## 🔖 Sobre o projeto  
Este projeto foi desenvolvido como exercício de prática para demonstrar a **conversão de JSON em objetos Java** utilizando a biblioteca Gson. Ele aborda diferentes cenários, desde JSONs completos até campos opcionais e estruturas aninhadas.

---

## 🎯 Funcionalidades

✔️ Permite a conversão de JSON para objetos Java com:

- Campos completos e obrigatórios  
- Campos opcionais (flexibilidade para JSONs parciais)  
- Estruturas aninhadas (objetos dentro de objetos, ex: Livro e Editora)  

---

## 🧠 Técnicas e conceitos utilizados

✅ Utilização da biblioteca Gson para serialização e desserialização JSON  
✅ Configurações avançadas com `GsonBuilder` (`serializeNulls()`, `setLenient()`)  
✅ Uso de records Java para modelagem simples e imutável dos dados  
✅ Manipulação de JSON aninhado com classes compostas (`Livro` e `Editora`)  

---

## 🚀 Tecnologias e ferramentas

- Java 17+  
- IntelliJ IDEA
- Git e GitHub
- Biblioteca Gson (Google)  

---

## 📂 Organização do Projeto
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

