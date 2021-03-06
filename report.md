# Assignment 02

## Group 28

| Name        | ID           |
| ------------- |:-------------:|
| Parth Chandratreya | 1441842 |
| Misha Wagner | 1436049 |
| Dom Williams | 1433805 |
| Dan Jones | 1427970 |

## The Linux commands

```
# compile
erlc tarrys.erl

# run
erl -run tarrys main -s init stop -noshell
```

## Terminal output

`
p q t r q s t s p s u t u s q r t q p
`

## How far you got

Assignment fully completed and correct

## Extra work undertaken

We created a script that reads an input filename from stdin, which generates a `docker-compose.yaml` file.

This can then be used to create the network as represented by the file, and nodes can only access nodes to which they have a connection.

Usage:
`./generate.py input.txt`

And to bring up the docker containers and network:
`docker-compose up`

This requires having python3, docker and docker-compose installed.
