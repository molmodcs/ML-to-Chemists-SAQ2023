# ML-to-Chemists-SAQ2023
Minicurso de Métodos de Aprendizagem de Máquina para Química

## Dicas sobre o uso do conda:

O conda é uma tool de gerenciamento de pacotes e ambientes do anaconda. Quando instalado o anaconda,
a ambiente "base" é definido como padrão e todas bibliotecas/módulos são instalados e configurados para este
ambiente. É recomendado que as atividades e projetos que serão criados sejam realizados em ambientes específicos
para cada aplicação que deseja. Isto porque se tentar instalar todos os pacotes no "base", depois certamente vão ocorrer
conflitos de versões já instaladas com as necessárias para a aplicação. Portanto, tenha sempre o cuidado de criar
um ambiente para cada aplicação.

## Criando um ambiente para a execução

conda create -n deepchem

## Ativando

conda activate deepchem

## Instalando o deepchem e todas as dependências

conda install -c conda-forge deepchem -y

