# porpose 
A simple java library to flat a Map<String, Object>

## sample 

### before flattening:

```sh
"properties": {
"id": {
"type": "integer"
}
```

### after flattening:

```sh
"/properties/id/type": "integer",
```