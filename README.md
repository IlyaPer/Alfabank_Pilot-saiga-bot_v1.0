# Alfabank_Pilot-saiga-bot_v1.0
A prototype of Alphachat bot for Alfabank employees, based on open neural network [Saiga2_7b_lora](https://huggingface.co/IlyaGusev/saiga2_7b_lora).
Pilot project for Alfabank from HSE students.

## Engeneering tasks
1) Generate and preprocess dataset
2) Import BERT model and train model via generated dataset
3) Fine tune BERT model
4) Import Saiga2_7b_lora, test different parameters of importing
5) Compare quality of answers
6) Use chosen model for generaating answers, came from telegram users
7) Test bot and quality of the model

## Further steps
1) Deploy on server with 32 Gb RAM, 256 Gb memory
2) Import Saiga2_30b_lora
3) Train model with data from Knowledge Base of Alfabank 

## Architecture of bot integration

![Architecture](./img/architecture.png)

## Example of bot usage on russian language.

![usage of the bot](./img/bot_usage.jpg)

