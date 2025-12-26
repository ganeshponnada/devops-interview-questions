# AWS Interview Notes

## Q1: What happens if an EC2 instance cannot access the internet?

**Answer:**
- Check Internet Gateway attached to VPC
- Verify route table has 0.0.0.0/0 to IGW
- Check Security Group outbound rules
- Check NACL rules
