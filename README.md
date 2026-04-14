# CadastroLocal

Aplicativo simples de cadastro de produtos desenvolvido com React Native e Expo.
Permite adicionar, listar e remover produtos com persistência local.
Projeto simples para estudo da faculdade.

---

## Funcionalidades

* Adicionar produtos
* Listar produtos cadastrados
* Remover produtos
* Persistência local com armazenamento no dispositivo

---

## Tecnologias

* React Native
* Expo
* React 19
* JavaScript / TypeScript
* React Hooks
* AsyncStorage
* React Navigation

---

## Bibliotecas

* @react-native-async-storage/async-storage (2.2.0)
* @react-navigation/native (^7.2.2)
* @react-navigation/stack (^7.8.10)
* expo (~54.0.33)
* expo-status-bar (~3.0.9)
* react (19.1.0)
* react-dom (^19.1.0)
* react-native (0.81.5)
* react-native-gesture-handler (~2.28.0)
* react-native-reanimated (~4.1.1)
* react-native-safe-area-context (~5.6.0)
* react-native-screens (~4.16.0)
* react-native-web (^0.21.2)
* react-native-worklets (^0.8.1)

---

## Estrutura do Projeto

```
CadastroLocal
│
├── dados
│   ├── Produto.ts
│   └── GestorDados.ts
│
├── ProdutoLista.js
├── ProdutoForm.js
├── ProdutoItem.js
├── CommonStyles.js
├── App.js
└── package.json
```

---

## ▶️ Como executar

### 1. Instalar dependências

```
npm install
```

### 2. Rodar o projeto

```
npx expo start
```

### 3. Executar

* Android → pressione `a`
* Web → pressione `w`
* iOS → pressione `i`

---

## Persistência de dados

Os dados são armazenados localmente utilizando AsyncStorage, permanecendo salvos mesmo após fechar o aplicativo.

---

