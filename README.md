# desafio-java-API-REST-utilizando-o-Java-17
desafio-java-API-REST-utilizando-o-Java-17
classDiagram
    class Person{
        <<Data>>
        - String name
    }

    class Account{
        <<Data>>
        - String number
        - String agency
        - Float balance
        - Float limit
    }

    class Feature{
        <<Data>>
        - String icon
        - String Disc
    }

    class Card{
        <<Data>>
        - String cardNum
        - Float cardLim
    }

    class News{
        <<Data>>
        - String newsIcon
        - String NewsDesc
    }

    Person --> Account
    Person --> Feature
    Person --> Card
    Person --> News
