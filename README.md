# Checkpoint-02-Casos-de-Uso-de-ML---Energia-Eólica-e-Energia-Solar
---
Integrantes:


Rafael Vaz - RM:566429

André Eduardo Martins RM:563297

Felipe Hui Hattori - RM:565169

---

## 💻 Instruções da Entrega

* A atividade pode ser desenvolvida em grupo.
* Apenas um integrante deve submeter o arquivo.
* Enviar apenas o link do repositório. Não envie arquivos .txt ou .pdf.
  

---

## 📊 Atributos do Dataset do Exercício 1 - Parte 1

O dataset utilizado no primeiro exercício contém os seguintes atributos, que descrevem o consumo de energia e as condições ambientais de uma casa ao longo do tempo.

* **date time**: ano-mês-dia hora:minuto:segundo
* **Appliances**: uso de energia de eletrodomésticos, em Wh
* **lights**: uso de energia das luminárias da casa, em Wh
* **T1**: Temperatura na área da cozinha, em Celsius
* **RH_1**: Umidade na área da cozinha, em %
* **T2**: Temperatura na sala de estar, em Celsius
* **RH_2**: Umidade na sala de estar, em %
* **T3**: Temperatura na área de serviço
* **RH_3**: Umidade na área de serviço, em %
* **T4**: Temperatura no escritório, em Celsius
* **RH_4**: Umidade no escritório, em %
* **T5**: Temperatura no banheiro, em Celsius
* **RH_5**: Umidade no banheiro, em %
* **T6**: Temperatura externa (lado norte do prédio), em Celsius
* **RH_6**: Umidade externa (lado norte do prédio), em %
* **T7**: Temperatura na sala de passar roupa, em Celsius
* **RH_7**: Umidade na sala de passar roupa, em %
* **T8**: Temperatura no quarto 2 do adolescente, em Celsius
* **RH_8**: Umidade no quarto 2 do adolescente, em %
* **T9**: Temperatura no quarto dos pais, em Celsius
* **RH_9**: Umidade no quarto dos pais, em %
* **To**: Temperatura externa (da estação meteorológica de Chievres), em Celsius
* **Pressure**: Pressão (da estação meteorológica de Chievres), em mm Hg
* **RH_out**: Umidade externa (da estação meteorológica de Chievres), em %
* **Wind speed**: Velocidade do vento (da estação meteorológica de Chievres), em m/s
* **Visibility**: Visibilidade (da estação meteorológica de Chievres), em km
* **Tdewpoint**: Ponto de orvalho (da estação meteorológica de Chievres), °C
* **rv1**: Variável aleatória 1, adimensional
* **rv2**: Variável aleatória 2, adimensional

 ---

## ⚡ Atributos do Dataset do Exercício 2 - Parte 1

O dataset deste exercício foca na dinâmica de um sistema de energia, incluindo o tempo de reação e o balanço de poder entre um produtor e múltiplos consumidores.

* **reaction time**: Tempo de reação para um participante do mercado de energia (Produtor ou Consumidor).
* **tau2**: Tempo de reação do Consumidor 1.
* **tau3**: Tempo de reação do Consumidor 2.
* **tau4**: Tempo de reação do Consumidor 3.
* **p1**: Balanço de poder do Produtor de energia.
* **p2**: Balanço de poder do Consumidor 1.
* **p3**: Balanço de poder do Consumidor 2.
* **p4**: Balanço de poder do Consumidor 3.
* **g1**: Coeficiente de elasticidade de preço (gamma) do Produtor de energia.
* **g2**: Coeficiente de elasticidade de preço (gamma) do Consumidor 1.

# ☀️ Dataset de Dados Meteorológicos (HI-SEAS)

Este dataset contém dados meteorológicos coletados pela estação **HI-SEAS**, abrangendo o período de **setembro a dezembro de 2016**.

---

## 📌 Atributos do Dataset

- **row number**: Número da linha (1-n), útil para ordenação dos resultados.  
- **time_t**: Data no formato UNIX (segundos desde 1º de janeiro de 1970), útil para ordenação com outros datasets.  
- **yyyy-mm-dd**: Data no formato ano-mês-dia.  
- **hh:mm:ss**: Horário local no formato 24 horas.  
- **numeric data**: Dados numéricos (pode ser uma string vazia).  
- **text data**: Dados textuais (pode ser uma string vazia).  

---

## 📐 Unidades de Medida

- **Solar radiation** ☀️: radiação solar (watts/m²).  
- **Temperature** 🌡️: temperatura (°F).  
- **Humidity** 💧: umidade relativa (%).  
- **Barometric pressure** 🌬️: pressão barométrica (polegadas de mercúrio, *Hg*).  
- **Wind direction** 🧭: direção do vento (graus).  
- **Wind speed** 💨: velocidade do vento (milhas por hora, *mph*).  
- **Sunrise / Sunset** 🌅: horário do nascer/pôr do sol (horário local do Havaí).  

---

## 📂 Período de Coleta
- Setembro a Dezembro de **2016**  

---

✍️ Este README descreve os atributos e unidades de medida do dataset para auxiliar no uso e análise dos dados.


