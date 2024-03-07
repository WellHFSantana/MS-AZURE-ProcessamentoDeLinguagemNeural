# MS-AZURE-ProcessamentoDeLinguagemNeural
Laboratório 3 - Microsoft Azure AI Fundamentals

Para fazer este laboratório, retirei um comentário de um produto postado no Mercado Livre e fiz a análise dos sentimentos. Abaixo seguem alguns prints do resultado da análise. Ao final, é possível encontrar o código JSON gerado. 

![image](https://github.com/WellHFSantana/MS-AZURE-ProcessamentoDeLinguagemNeural/assets/53205033/62dcc35f-0c71-4093-8264-b5fddf202adb)


{
    "documents": [
        {
            "id": "id__2228",
            "sentiment": "negative",
            "confidenceScores": {
                "positive": 0,
                "neutral": 0,
                "negative": 1
            },
            "sentences": [
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 0,
                    "length": 256,
                    "text": "Usei apenas uma vez e nao quer ligar mais, gostaria de um retorno pois um produto que se e usado apenas uma vez e ja dar defeito não deveria nem ser colocado a venda, mesmo sendo valor baixo mais deveria ter uma vida util bem melhor ne, muito insatisfeito.",
                    "targets": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.01,
                                "negative": 0.99
                            },
                            "offset": 74,
                            "length": 7,
                            "text": "produto",
                            "relations": [
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/0/assessments/0"
                                },
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/0/assessments/1"
                                }
                            ]
                        }
                    ],
                    "assessments": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0,
                                "negative": 1
                            },
                            "offset": 121,
                            "length": 7,
                            "text": "defeito",
                            "isNegated": false
                        },
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.02,
                                "negative": 0.98
                            },
                            "offset": 243,
                            "length": 12,
                            "text": "insatisfeito",
                            "isNegated": false
                        }
                    ]
                }
            ],
            "warnings": []
        }
    ],
    "errors": [],
    "modelVersion": "2022-11-01"
}
