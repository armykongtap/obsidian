
- ช่วยนักลงทุนที่ไม่รู้จะลงทุนอะไร
- model ต้องเปิดเผยนักลงทุน
- เทรดน้อย รายเดือน/รายปี
- hidden markov model / clustering

# New guru
1. Fintech Add Modelers - Name, email
2. Guru Create Model
	1. create via website
	2. upload backtest signal 
	3. backtest
3. Broker Launch model
4. Update daily signal
# Upload signal

https://gitlab.devcula.com/fintech/finnize-model

`https://admin-gateway.finnize.com/api/model/signal/add?apiKey={api_key}&apiSecret={api_secret}"`

Body
```
{
   "modelName":"RF Dividend Factor [Managed Risk]",
   "lastSignalDate":"2023-04-04",
   "modelSignals":[
	  {
		 "signalDatetime":"2023-04-03",
		 "symbol":"AP",
		 "action":"HOLD",
		 "amountType":"PCT_PORT",
		 "amountValue":0.1
	  },
	  {
		 "signalDatetime":"2023-04-03",
		 "symbol":"INTUCH",
		 "action":"HOLD",
		 "amountType":"PCT_PORT",
		 "amountValue":0.1
	  }
   ]
}
```

Upload backtest signal - ให้ modelSignals ย้อนหลังทั้งหมด
Upload daily signal - ให้ modelSignals มีแค่วันล่าสุดวันเดียว


