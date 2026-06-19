- deploy tfex gotrade

migrate model conductor dev
- turn on rds nonprod https://ap-southeast-1.console.aws.amazon.com/rds/home?region=ap-southeast-1#databases:
- dump and restore to new database
- turn on model-condctor-dev uncomment
- sanity test
- delete nonprod database

migrate model conductor prod
- move fluxcd
- dump and restore to new database
- turn off model-condctor-prod old
- turn on model-condctor-prod new
- sanity test

d-vote
- after move all fintech ?, remove taint