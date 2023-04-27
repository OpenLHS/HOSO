# HOSO Ontology Documentation

[//]: # "This file is meant to be edited by the ontology maintainer."

Welcome to the HOSO documentation!

You can find descriptions of the standard ontology engineering workflows [here](odk-workflows/index.md).

## Schema

![Screenshot](img/HOSO.png)

## Classes

|IRI         |value                                    |def                                                                                                                                                                                                                                   |
|------------|-----------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|HOSO_0000003|healthcare service organism specification|A service agreement specification identifying an organism for whom a healthcare service delivery aims at providing a desired effect to its health status.                                                                             |
|HOSO_0000004|healthcare facility                      |TBD                                                                                                                                                                                                                                   |
|HOSO_0000005|health worker role                       |A role that inheres in an organism as a consequence of a training of this organism to perform in some health procedures.                                                                                                              |
|HOSO_0000006|healthcare organization role             |A role that inheres in an organisation and is realized by providing some healthcare service delivery.                                                                                                                                 |
|HOSO_0000007|health worker                            |An organism that is the bearer of a health worker role.                                                                                                                                                                               |
|HOSO_0000008|healthcare organization                  |An organisation that bears a healthcare organisation role.                                                                                                                                                                            |
|HOSO_0000009|healthcare worker                        |A health worker who is a member of a healthcare organisation.                                                                                                                                                                         |
|HOSO_0000010|healthcare procedure                     |A health procedure that is part of a healthcare service delivery and that is performed by a healthcare worker while realizing its health care worker role.                                                                            |
|HOSO_0000011|healthcare organization service delivery |A service delivery under the responsibility of a healthcare organisation. It stems from an agreement between a requesting agent and a healthcare organisation.                                                                        |
|HOSO_0000012|healthcare service                       |A healthcare organisation service delivery that aims at providing a desired effect on the health status of individuals and their communities. It is usually composed of health procedures and possibly associated ancillary processes.|
|HOSO_0000013|ancillary care service delivery          |A healthcare organisation service delivery that aims to support healthcare services without directly providing a desired effect on the health status of individuals or communities.                                                   |
|HOSO_0000014|custodial care service delivery          |A healthcare organisation service delivery that aims to provide for the activities of daily living of individuals or communities.                                                                                                     |
|HOSO_0000015|individual healthcare service            |A healthcare service where the targeted organism intended to have a desired effect of some health procedure is specified.                                                                                                             |
|HOSO_0000016|populational healthcare service          |A healthcare service that aims at providing a desired effect on the health status of a community.                                                                                                                                     |
|HOSO_0000017|healthcare encounter                     |A temporally-connected individual healthcare service that aims to improve, maintain or restore the health of some participating organism.                                                                                             |
|HOSO_0000018|facility-based healthcare encounter      |A healthcare encounter during which the recipient is located in a healthcare facility at some time.                                                                                                                                   |


## Properties

|IRI         |value                      |def|
|------------|---------------------------|---|
|HOSO_0000001|has participating performer|TBD|
|HOSO_0000002|has participating recipient|TBD|
