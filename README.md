# Análise de Sentimentos com Azure Language Studio
🚀 Este projeto usa **Azure Cognitive Services** para análise de sentimentos em texto.

## 📂 Estrutura do projeto
- `inputs/sentences.txt` → Sentenças de teste para análise.
- `outputs/results.json` → Resultados extraídos do Azure.
- `README.md` → Documentação do processo.

## 🔍 Como funciona?
1. As frases foram analisadas no **Azure Language Studio**.
2. O serviço retornou insights como:  
   - **Polaridade do sentimento** (Positivo, Negativo, Neutro).  
   - **Entidades identificadas** (nomes de empresas, locais, datas).  
   - **Frases-chave** extraídas.  

## 📊 Exemplos de Resultados

Analise do documento

![image](https://github.com/user-attachments/assets/0eb6b395-7b78-44eb-ad57-acbbc524f349)

Sentenca 1 
input
Detectamos um aumento incomum no tráfego de rede nas últimas 24 horas.
Output
![image](https://github.com/user-attachments/assets/41992b92-5c46-40ad-809d-a88950b59dd4)

Sentenca 2 
input
Recebemos um e-mail suspeito pedindo credenciais de login.
Output
![image](https://github.com/user-attachments/assets/55d52dd5-43eb-403e-8eeb-54e47b93b09d)

Sentenca 3
input
O sistema identificou múltiplas tentativas de acesso falhas de um mesmo IP.
Output
![image](https://github.com/user-attachments/assets/01a986ae-fed4-4727-88b4-56aca3570c89)

Sentenca 4
input
Usuários relataram que suas contas foram comprometidas após um ataque de phishing.
Output
![image](https://github.com/user-attachments/assets/d85be98d-5ebd-48d3-9dea-6097d0340bb9)

Sentenca 5
input
O antivírus bloqueou um malware disfarçado de documento PDF.
Output
![image](https://github.com/user-attachments/assets/df73aca9-f5c8-44c6-bdb2-eebf6beffe7c)

Sentenca 6
input
A autenticação multifator ajudou a prevenir um possível ataque de força bruta.
Output
![image](https://github.com/user-attachments/assets/8e58f6bb-e4ff-4f8d-918b-af9748c34fd3)

Sentenca 7
input
Detectamos uma comunicação não autorizada entre dispositivos internos e um servidor externo.
Output
![image](https://github.com/user-attachments/assets/a18b78d7-a85f-4576-9d6a-4a0ad95435d7)

Sentenca 8
input
A criptografia dos dados impediu que invasores acessassem informações confidenciais.
Output
![image](https://github.com/user-attachments/assets/b13b536d-1696-44aa-a782-1d2ef09d9598)

Sentenca 9
input
Um ransomware criptografou arquivos críticos e está exigindo pagamento em Bitcoin.
Output
![image](https://github.com/user-attachments/assets/6497575f-f4d3-4a89-88ed-84585751da9d)


Sentenca 10
input
Os logs mostram um comportamento anômalo que pode indicar um movimento lateral na rede.
Output
![image](https://github.com/user-attachments/assets/d2e58188-eee2-429f-9df4-bab860632af0)

Texto Original 
![image](https://github.com/user-attachments/assets/568d92b7-53f3-4fd4-a653-a1d739526be7)


## 📌 Insights
- A IA conseguiu detectar corretamente sentimentos em frases curtas.
- Frases com eventos concretos (ex: phishing, ransomware) são bem detectadas
- O modelo não identificou corretamente alguns contextos
- A maioria das sentenças foi classificada como negativa



