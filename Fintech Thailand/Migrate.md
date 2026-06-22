# Gitlab devcula
- save ~2,600 thb/m
- pros
	- code เดิมอยู่
	- ฟรี
	- role manage
- cons
	- insecure
	- no backup

# List project  EKS
- finnize sbito (อาจจะปิด) - fix ip?
- finnize globlex (อาจจะปิด)  
- model-conductor UOB
- fintech  
	- job-byd-bill
	- job-byd-snapshot
	- service-byd-twap
	- job-scb-gen signal
		- poc kubernetes egress fix ip
# List Project DOKS
- model conductor GBS
- opta (dev)
- fintech (off, in eks)
- finnize-webull (dev)
- gotrade (off)
# Kubernetes devcula
- 4,200 (share) + 600 (10% of ec2,rds,etc) thb/m
- d-vote
	- fintech ย้ายออก 7,000 -> 11,000
	- วางไว้สำหรับ scale ใหญ่  ถ้าปัจจุบันควรจะ 4000 thb
- task
	- fluxcd to new format
	- migrate database
	- IP - scb, sbito ?, gbs ?
# Kerbernetes GCP
- ~$108–123/month - ราคาพอๆกัน ลด spec database นิดหน่อย
- pros
	- google own k8s
	- multi region cluster / Bangkok region - หุ้นอาจจะจำเป็น
	- ปัญหาน้อยกว่า DO
	- Autopilot Compute อาจจะถูกลง ?
- cons
	- แพงกว่า 40%
	- more complex
- tasks
	- poc GCP
	- migrate database
	- minor edit fluxcd
# Fintech AWS
- rds fintech public data 1,760 thb/m
- EC2 1,100 thb/m - finnize globlex k'john
	- 2026-06-09 Momentum pro, Price factor, Trend Factor, Rythm Pro ไม่มีคนใช้แล้ว
- finnize GBS
	- 2 account AUM 40,000
	- 5 smart grid น่าจะ model conductor
	- ปิดบริการ
		- แจ้งลูกค้า
		- commission smart grid จาก model conductor ?
- finnize SBITO
	- revenue 3,000 thb/m
- model conductor UOB

# Saving
- AWS devcula
	- Kubernetes EC2 6 -> 3 save ~100$
	- RDS nonprod micro off save ~12$
