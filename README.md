## Simple REST API 
This example demonstrates how to setup a RESTful Web Services to list, get, create, delete and update Pokémons.
    list...... GET /pokemons/
    get....... GET /pokemons/<pokemon_id>
    create.... POST /pokemons/
    delete.... DELETE /pokemons/<pokemon_id>
    update.... PUT /pokemons/<pokemon_id>

## AWS Resources Used
AWS Lambda: https://aws.amazon.com/lambda/
AWS APIGateway: https://aws.amazon.com/api-gateway/
AWS DynamoDB: https://aws.amazon.com/dynamodb/
PokemonStoreCdkStack(app, "pokemon-store-cdk", env={'region': 'us-west-2'})

## Strcture
This web service has a seperate file for each Pokémon action.

## Usage
### List all Pokémons 

```bash
curl https://XXXXXXX.execute-api.us-east-1.amazonaws.com/dev/pokemons
```

Example output:
## Useful commands

 * `cdk ls`          list all stacks in the app
 * `cdk synth`       emits the synthesized CloudFormation template
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk docs`        open CDK documentation

Enjoy!
