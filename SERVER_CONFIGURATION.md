## TYPE
Cloud - AWS

## Location
Server placement United States

## INFO
- m5.12xlarge + 48 vCPU 
RAM 192 GB + storage 16TB total + network bandwidth 5'000Mbps
- Use EBS snapshot backup. mount EBS Volume & rsync & snapshot (auto-backup)
- Use AWS-CloudWatch statue check and Auto-Recovery
- We are in procedure of designing a backup and live swap architecture(replication and master-slave swap) in case of the node fails in real-time.
