### mlproject-ANN
## Previsão de abandono de Clientes de banco

Este projeto é uma aplicação Streamlit projetada para prever a probabilidade da saida de clientes de um banco. O modelo utiliza dados de clientes e um modelo de deep learning treinado com TensorFlow para fornecer insights sobre a possibilidade de um cliente deixar o banco.

O aplicativo permite a entrada dos seguintes atributos dos clientes:

*Geografia: Localização geográfica do cliente (codificado com one-hot encoding).

*Gêneo: Gêneo do cliente (codificado com label encoding).
*Idade: Idade do cliente (18-92).

*Saldo: Saldo na conta do cliente.

*Pontuação de Crédito: Pontuação de crédito do cliente.

*Salário Estimado: Salário anual estimado do cliente.

*Tempo de Relacionamento: Número de anos que o cliente está com o banco (0-10).

*Número de Produtos: Número de produtos que o cliente possui (1-4).

*Possui Cartão de Crédito: Indica se o cliente possui cartão de crédito (0: Não, 1: Sim).

*É Membro Ativo: Indica se o cliente é um membro ativo (0: Não, 1: Sim).


Nesse repositório tem:

app.py: O script principal da aplicação Streamlit.

model.h5: O modelo TensorFlow treinado.

label_encoder_gender.pkl: LabelEncoder ajustado para a feature gêneo.

onehot_encoder_geo.pkl: OneHotEncoder ajustado para a feature geografia.

scaler.pkl: StandardScaler ajustado para escalonar os dados numéricos.

trainermodelo.ipynb: o notebook que treina o modelo e gera os arquivos h5 e pkl.

salaryregression.ipynb: Outro notebook usado para gerar os pkl e o modelo para a previsão da feature de salario, usando regressão.

hyperparametertuningann.ipynb: versão da predição de abandono do clique usando tuning de hiperparametros.
