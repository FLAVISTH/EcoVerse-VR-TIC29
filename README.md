# EcoVerse-VR-TIC29
# 🌐 EcoVerse VR — Experiência Interativa no Metaverso

## 👤 Nome do Aluno
Flavia Tainara

---

## 🎮 Apresentação do Projeto

O projeto **EcoVerse VR** consiste em um ambiente virtual imersivo desenvolvido no contexto do Metaverso, com foco em educação ambiental.

A experiência simula um parque ecológico interativo onde o usuário pode explorar o espaço e interagir com objetos relacionados à reciclagem.

---

## 🌍 Contexto e Objetivos

O projeto está inserido no contexto de educação no metaverso, com o objetivo de:

- Incentivar práticas de sustentabilidade  
- Tornar o aprendizado mais interativo  
- Simular situações reais de forma imersiva  

Problema:
Baixo engajamento em métodos tradicionais de ensino.

Solução:
Ambiente VR interativo com aprendizado prático.

---

## 🏗️ Estrutura do Ambiente

- Plano de chão (terreno)
- Árvores (ambiente natural)
- Lixeiras de reciclagem
- Objetos coletáveis
- Skybox configurado

---

## 🧠 Interação

O usuário interage com objetos que mudam de cor ao serem clicados.


### 💻 Script em C#

```csharp
using UnityEngine;

public class InteracaoSimples : MonoBehaviour
{
    public Renderer objetoRenderer;

    void OnMouseDown()
    {
        objetoRenderer.material.color = Color.green;
    }
}
```
## ⚙️ Processo de Criação

O desenvolvimento do projeto seguiu as seguintes etapas:

1. Criação do projeto no Unity
2. Configuração do XR Plugin Management
3. Estruturação do ambiente com objetos 3D
4. Implementação da interação em C#
5. Testes no modo Editor (PC)

---

## ⚠️ Dificuldades Encontradas

Durante o desenvolvimento, foram identificadas algumas limitações:

- Computador com apenas 4GB de RAM
- Travamentos ao executar o Unity
- Alto consumo de memória

Solução adotada:
Foi realizado o planejamento completo do projeto, com foco na estrutura, lógica e documentação.

---

## 🚀 Melhorias Futuras

- Implementação de multiplayer no ambiente
- Adição de efeitos sonoros
- Criação de animações interativas
- Integração com tecnologias Web3

---

## 📁 Estrutura do Repositório

/Assets  
/Scripts  
/Prefabs  
/Materials  

/ProjectSettings  
/Packages  

---
## ✅ Considerações Finais
O projeto demonstra a aplicação dos conceitos de Realidade Virtual e Metaverso, mesmo diante de limitações técnicas, evidenciando a capacidade de planejamento e organização.