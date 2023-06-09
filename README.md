# Gill Freshness Detection

 <h1>API Docs</h1>

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/15710919-02c12464-72c8-4a52-a955-656d1592b021?action=collection%2Ffork&collection-url=entityId%3D15710919-02c12464-72c8-4a52-a955-656d1592b021%26entityType%3Dcollection%26workspaceId%3D47d7d502-7365-4157-97be-2f07577bb417)

---

Base URL:

 <p >
  <a href="https://freshness-gill-prediction-api-mps7ogpvxa-et.a.run.app/">freshness-gill-prediction-ml-api</a>
</p>

### Prediksi Ikan
- Endpoint
  - /predict
- Method
  - POST
- Request Body
  - file = files
- Response

```json
{
    "prediction": "Tidak Segar"
}
```
_note: file .h5 di .gitignore karena ukuran terlalu besar dan sudah disertakan pada branch model machine learning_
