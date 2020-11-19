# bank-list
List of banks and related information such as legal name, link etc.

## Currently available lists

### Brazil

Data is available [here in json format](src/Brazil.json) and it follows the format below:
```json
{
  "001": {
    "nick": "BB",
    "name": "BANCO DO BRASIL S/A",
    "ispb": "00000000",
    "link": "www.bb.com.br"
  }
}
```

1. `001`: Object key, is also the bank code (a three number long code);
2. `nick`: An optional string with the Bank's nickname, or its more commonly known name;
3. `name`: A required string, the Bank's legal name;
4. `ispb`: An optional string representing the Bank's Brazilian Payment System Identifier, it's a number used by Brazil's Central Bank;
5. `link`: An optional string indicating Bank's website.

**Sources**

All data present in this file was extracted from the following sources:

- https://www.conta-corrente.com/codigo-dos-bancos/
- https://www.codigobanco.com/

## Contributing

Feel free to open a new pull-request to add new banks, details or countries.

## License

This library is licensed under the [MIT License](LICENSE).
