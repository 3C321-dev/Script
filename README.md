
# 🛡️ Laboratório de Cibersegurança: Simulação de Malware e Análise Defensiva

Repositório criado para fins educacionais e de pesquisa no contexto de estudos em cibersegurança, abordando a análise de comportamento de ameaças (Ransomware e Keylogger) desenvolvidas em Python e as respectivas práticas de mitigação e defesa.

---

## ⚠️ Disclaimer (Aviso Legal)
> *Este material e os códigos contidos neste repositório têm caráter **estritamente educacional**. O autor não se responsabiliza pelo uso indevido das informações ou scripts aqui apresentados. Testes de segurança e execução de scripts de simulação de ameaças devem ser realizados exclusivamente em ambientes isolados (máquinas virtuais/sandboxes) e com autorização explícita.*

---

## 📚 Sumário do Laboratório
O conteúdo deste projeto é baseado nas etapas práticas do laboratório de segurança:

1. **Fundamentos e Ambiente**
   - [Introdução](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/d16a4dc8-b8e6-496d-8b76-c22d32164648?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica) aos conceitos de ameaças.
   - [Exemplos de Malware](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/f7687784-1223-4795-a381-5b7ed35e97bb?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica) e análise comportamental.
   - [Construindo nosso Ambiente](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/9409acd4-11a7-426b-a635-954c8d5f41b9?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica) de testes isolado.

2. **Simulação de Ransomware (Criptografia Simétrica)**
   - [Criando as funções do Ransomware](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/0df83a4c-6797-40b8-b272-ef3f4196fe0a?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica) e [Analisando os códigos das funções](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/03c8366d-3a05-499d-a23d-402e91991926?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica).
   - [Executando o Script e Criptografando os Arquivos](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/75d9b4d3-0691-4560-899c-20e2439e8a99?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica).
   - [Descriptografando os Arquivos](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/5da780c4-21fa-40b7-b596-f19e7eb6a54b?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica) para recuperação de dados.

3. **Monitoramento e Captura de Dados (Keylogger)**
   - [Keylogger](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/86fa3b3d-5de1-47d9-a4d8-c2a066724445?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica) e [Criando nosso Keylogger](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/bdae2130-488e-4954-9187-963fbe0d1ca7?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica) utilizando a biblioteca `keyboard`.
   - [Rodando o arquivo keylogger.py](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/6fa4c154-555e-40af-a6ee-0b3e626bca53?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica) localmente.
   - [Tornando o Keylogger invisível para o usuário](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/22a89e57-be83-4541-b4d4-f46fd90d02f3?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica) (execução oculta em segundo plano).
   - [Enviando dados capturados remotamente ao atacante](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/3274b0f8-4a22-4508-baf1-4b37cb20499f?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica) e [Exportando dados em ambiente controlado](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/3b455f59-64be-46ed-9d95-5388c6669ecb?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica).

4. **Defesa e Mitigação**
   - [Como podemos nos proteger?](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/dceac60b-1b7c-4845-b7f3-9df48b8aad88?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica) Estratégias de resposta a incidentes e hardening.
   - [Entendendo o Desafio](https://web.dio.me/lab/simulando-um-malware-de-captura-de-dados-simples-em-python-e-aprendendo-a-se-proteger/learning/dd3f8a01-98f9-48c9-9fc9-a68c23ae4bd5?back=/track/bootcamp-santander-ciberseguranca-do-zero-a-pratica) e consolidação do aprendizado.

---

## 💻 Exemplos de Código

### 1. Criptografia de Arquivos (Ransomware Lab)
Exemplo prático utilizando a biblioteca `cryptography` para simular o bloqueio e a reversão de arquivos de texto:

```python
from cryptography.fernet import Fernet

# Geração de chave simétrica para testes
key = Fernet.generate_key()
f = Fernet(key)

# Leitura e cifragem do arquivo alvo
with open("arquivo_teste.txt", "rb") as file:
  dados = file.read()

dados_criptografados = f.encrypt(dados)

with open("arquivo_teste.txt.locked", "wb") as file:
  file.write(dados_criptografados)
print("[+] Arquivo criptografado com sucesso.")
