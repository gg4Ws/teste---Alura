descrição de curso teste - Alura

CONCEITOS DO GIT

1. Repositórios, commits e árvores (Trees)
   
    -> Um REPOSITÓRIO é como uma pasta ou diretório que contém todos os arquivos e o histórico de um projeto.

    Já o termo COMMIT pode ter como tradução literal “compromisso”, que seria uma ação em que você faz uma alteração no projeto, se compromete e salva suas alterações no            histórico do projeto. Ou seja, cada commit é uma entrada no histórico que contém informações sobre as alterações feitas. Sendo assim, ele é como um "ponto de salvamento",       uma fotografica de um instante, registrando as mudanças que foram efetuadas desde o ultimo commit
    Árvores, por último, representam a estrutura do diretório e arquivos em um commit específico, que tem como função registrar a organização do projeto ao longo do histórico       de desenvolvimento.

2. Ramificações (Branches) e fusões (Merges)

   -> As “ramificações” ou BRANCHES permitem que você crie linhas separadas de desenvolvimento para trabalhar em recursos ou correções sem afetar a linha principal do projeto.
      Cada branch é uma ramificação independente do código-fonte, possibilitando que você isole e desenvolva novas funcionalidades, refatore o código ou faça correções e testes       em paralelo, sem interferir no código existente na branch principal, que geralmente é nomeada como "main".
      
      Em um projeto com branches diferentes, a fusão, ou MERGE, permite combinar as alterações dessas branches de volta à linha principal, quando as alterações estão prontas.

CONCLUSÃO -> o estado de reprodução principal do projeto esta na Main, e as Branchs são linhas independentes de desenvolvimento, na quais são realizados Commits para as mais diversas funcionalidades(testes, mudanças,etc.); essas branchs podem(ou nao) fazer parte da main, a partir do Merge.
