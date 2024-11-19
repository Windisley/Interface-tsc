# Interface e Exemplo de Uso: `DadosPerson`

Este código define uma **interface** em TypeScript chamada DadosPerson, que serve como um contrato para a estrutura de um objeto. Em seguida, é criado um exemplo prático de um objeto data que implementa essa interface.

![interface](https://github.com/user-attachments/assets/9a626cd0-0834-4d81-8cc3-37efa011432a)

## Definição da Interface

A interface `DadosPerson` possui os seguintes campos:
- **id** (`string`): Identificador único da pessoa.
- **Name** (`string`): Nome da pessoa.
- **year** (`number`): Idade ou ano relacionado à pessoa.
- **life** (`boolean`): Indica se a pessoa está viva (true) ou não (false).

### Código:
    typescript
interface DadosPerson {
    id: string;
    Name: string;
    year: number;
    life: boolean;
}
