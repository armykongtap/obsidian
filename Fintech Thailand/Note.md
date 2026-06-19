
- บริษัทไม่มี repeatable revenue engine ที่สร้างงานเองได้
- หยุดมองตัวเองเป็น software house คุณควรไปทาง:
	- financial infrastructure
	- managed service
	- platform
	- compliance/data/reporting layer - สร้าง flagship product แค่ 1 ตัว
- Deployment + Infra

Product
- B2B / B2B2C
	- Trading Infrastructure & Automation Platform
	- Model Conductor
	- Forex
		- pain point ib จัดการ retail
- B2C (for advertise)
	- Webull connector
	- Thai Port Tracker — แอปติดตามพอร์ตหุ้นไทย
		- asset - กองทุน พันธบัตร หุ้นไทย หุ้นนอก บัญชีเงินฝาก crypto หนี้ ผ่อน
		- how to track - manual input, อ่านเมล, settrade open API
		- เคยจะทำแล้ว รอโครงการ your data
		- fintech ต่อ settrade, ขอทุน CMDF
		- อาม pentest, ic license
		- yahoo finance ราคาหุ้น
		- รายได้ subscription fee, โฆษณา, affiliate , b2b white label, ขายข้อมูล
	- Stock screener
	- Backtest playground
- Self
	- DR Webull Arbitrage
	- Polymarket Arbitrage / MM
		- LMSR
	- hummingbot 
		- kubernetes
		- settrade
			- วาง GTC เพื่อคิวแรก
		- arbitrage
			- spot-future index / single stock
			- DR
			- bitkub

pi securities รับ tradingview webhook ผ่าน settrade open api
สิ่งที่ broker ต้องมี
1. Settrade Open API with Login via Settrade (pdf แนบมาด้วย) - key, secret
2. settrade open api - marketrep api key, secret
QA
- เปลี่ยน logo/theme?
- app ไม่ได้ lock ให้เฉพาะลูกค้าที่กำหนด
- MP-MTL order
- account ที่ trade ได้

TODO
- Deploy optatrader.com
- Deploy xxx.gotrade.tech - รอ pi
- Deploy xxx.gotrade.tech - รอ globlex

คุณนัท
- [ ] opta - tradingview forex
	- [ ] เรื่องจด domain
	- [ ] deal broker อยู่
	- [ ] pi security ผ่าน settrade open api
	- [ ] ปลายเดือน move gotrade to opta
- [x] optix - options calculator
	- [x] อยากได้เพิ่มอะไร เช่น screener
	- [x] Unusual options activity alerts
	- [ ] รอคุยพร้อมพี่เกียร์
- [ ] Webull algo trade SaaS (3commas)
	- [ ] คอนเฟิมว่าจะมีลูกค้าใช้
	- [ ] theme ตาม https://elysiumtrader.com/
	- [ ] ทำ Landing page + ปุ่ม join whitelist
	- [ ] ลองสัมภาษณ์รายใหญ่ต้องการอะไร
	- [ ] ถาม webull มี user request ขอ Auto Trade / Bot บ้างมั้ย? ขออะไร เช่น grid, rebalance?
	- [x] rebalance
	- [ ] https://www.figma.com/design/R7grpjNhGpEUn7ibpJvWnC/Finnize-Gotrade?node-id=1948-7749&p=f&t=XtSzqHDBHO5IAS2G-0
- [ ] ทำ smart port - รอคุยกับ iba กับพี่เกียร์เริ่มยังไง


พี่ต่อ
- [ ] API ถอนเงิน - ให้ถอนเงินปกติ
	- [ ] ลูกค้า แสดงผลกำไรไม่ถูกต้อง, ซื้อขายไม่ถูกต้อง
	- [ ] gbs ง่ายขึ้น ?
	- [ ] มี guru ใหม่ - รอ
- [ ] Product idea - Product ที่ทำให้ trade เยอะขึ้น
	- [x] Demand B2B software ยาก
	- [x] Product ที่ทำให้ trade เยอะขึ้น
	- [ ] Spread
		- [ ] เจ้าของหุ้น - ต้องการ liq ไม่สนกำไร
		- [ ] trader - ต้องการกำไร
		- [ ] รอถามอีกรอบ
- [ ] ขอปิด model คุณจอน

พี่มั่ง
- [x] งาน tisco
- [ ] Pentest ?
