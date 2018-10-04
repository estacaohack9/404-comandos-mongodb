## COMANDOS PARA DATABASES
show databases

use nomedobanco

## COMANDOS PARA COLLECTIONS

show collections

db.dropDatabase()

## COMANDOS PARA DOCUMENTS

db.nomedacolecao.find({`query`})

db.nomedacolecao.insert({`novosDados`})

db.nomedacolecao.update({`query`}, {`novosDados`})

db.nomedacolecao.remove({`query`})

db.nomedacolecao.drop()
