# ABN Tikkie API
access token: meSyLAITU0DGi4q4oloDXFqvAMmA

tikkie platform code:
2b697ddf-4e0f-424d-88be-4127cbd480ff

### POST USER Joris:
{
  "userToken": "95e36135-33c1-4abd-84c9-3f96eb11d135",
  "name": "Joris",
  "status": "ACTIVE",
  "bankAccounts": [
    {
      "bankAccountToken": "fea08c36-b320-4d41-ba78-19d486c5b514",
      "iban": "NL82ABNA0236536203",
      "label": "Personal account"
    }
  ]
}

### POST Payment requests:
{
  "paymentRequestUrl": "https://acc.tikkie.me/pay/ovnb659nolsai8curiad",
  "paymentRequestToken": "ovnb659nolsai8curiad",
  "externalId": "Invoice: 4567"
}

### GET Payment requests: 
https://api-sandbox.abnamro.com/v1/tikkie/platforms/2b697ddf-4e0f-424d-88be-4127cbd480ff/users/95e36135-33c1-4abd-84c9-3f96eb11d135/paymentrequests?page=1&size=3

{
  "paymentRequests": [
    {
      "token": "c18081k4s5rp5gl76tlv",
      "amountInCents": "2500",
      "currency": "EUR",
      "description": "Pizza",
      "created": "2017-06-10T09:37:56.249Z",
      "expired": null,
      "status": "OPEN",
      "bankAccountYieldedTooFast": false,
      "externalId": "Invoice: 4567",
      "payments": []
    },
    {
      "token": "ovnb659nolsai8curiad",
      "amountInCents": "2500",
      "currency": "EUR",
      "description": "Pizza",
      "created": "2017-06-10T09:35:28.128Z",
      "expired": null,
      "status": "OPEN",
      "bankAccountYieldedTooFast": false,
      "externalId": "Invoice: 4567",
      "payments": []
    }
  ],
  "totalElements": 2
}


### POST User Orhan:
{
  "userToken": "64386690-1dc4-4397-9e7f-62a670b9e274",
  "name": "Orhan",
  "status": "ACTIVE",
  "bankAccounts": [
    {
      "bankAccountToken": "64403431-8a01-4829-8891-d6ccf94b5292",
      "iban": "NL28ABNA0571277676",
      "label": "Personal account"
    }
  ]
}

### POST Payment request Orhan:
{
  "paymentRequestUrl": "https://acc.tikkie.me/pay/7ee16rp0ufjo5tkes0a4",
  "paymentRequestToken": "7ee16rp0ufjo5tkes0a4",
  "externalId": "Invoice: 5000"
}



### POST User Yogesh:
{
  "userToken": "f6d54d13-4568-4f97-8b7e-098ecd716b5a",
  "name": "Yogesh",
  "status": "ACTIVE",
  "bankAccounts": [
    {
      "bankAccountToken": "54bf8e76-bda9-42db-b2d2-179bea7d77c5",
      "iban": "NL83ABNA0597536138",
      "label": "Personal account"
    }
  ]
}

### POST Payment Yogesh:
{
  "paymentRequestUrl": "https://acc.tikkie.me/pay/nngmb3n5cd29u3m3pmh5",
  "paymentRequestToken": "nngmb3n5cd29u3m3pmh5",
  "externalId": "Invoice: 6200"
}
