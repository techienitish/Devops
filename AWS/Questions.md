𝐂𝐈/𝐂𝐃 𝐚𝐧𝐝 𝐏𝐢𝐩𝐞𝐥𝐢𝐧𝐞𝐬

**Q:  Your deployment pipeline frequently fails at random stages. How do you make it more reliable & fix this issue ?**
 
- First of all, analyse the logs and identify which stage is failing.
- Monitor Resource Utilization: Check system resources (memory, CPU, disk space) on CI/CD agents/runners during failures.
- Validate the availability and stability of external services, APIs, or artifacts involved in the pipeline.
- Break down the pipeline into smaller, independent stages with clear inputs and outputs
- Implement automated rollback strategies when a deployment fails to ensure minimal downtime.
- Use blue/green or canary deployment techniques to reduce the impact of failures.

**Q: The product team wants faster releases, but your builds are slow. How do you speed up without breaking things?**

𝐈𝐧𝐟𝐫𝐚𝐬𝐭𝐫𝐮𝐜𝐭𝐮𝐫𝐞 𝐚𝐬 𝐂𝐨𝐝𝐞
→ Your Terraform script works in dev but crashes in prod. What’s your next step?
→ A junior accidentally deleted critical infrastructure using IaC. How do you prevent this next time?

𝐌𝐨𝐧𝐢𝐭𝐨𝐫𝐢𝐧𝐠 𝐚𝐧𝐝 𝐎𝐛𝐬𝐞𝐫𝐯𝐚𝐛𝐢𝐥𝐢𝐭𝐲
→ A service went down at 2 AM. You weren’t alerted. What would you fix in your monitoring setup?
→ You have logs, metrics, traces — but you’re still blind during outages. What’s missing?

𝐂𝐨𝐧𝐭𝐚𝐢𝐧𝐞𝐫𝐢𝐬𝐚𝐭𝐢𝐨𝐧 𝐚𝐧𝐝 𝐊𝐮𝐛𝐞𝐫𝐧𝐞𝐭𝐞𝐬
→ Your Kubernetes cluster runs out of resources often. How would you manage and optimise it?
→ One pod works, the other fails with the same image. How would you debug it?

𝐒𝐞𝐜𝐮𝐫𝐢𝐭𝐲 𝐚𝐧𝐝 𝐀𝐜𝐜𝐞𝐬𝐬 𝐂𝐨𝐧𝐭𝐫𝐨𝐥
→ Developers have too many permissions in production. How would you enforce least privilege?
→ A secret got exposed in a Git commit. What steps would you take now and for future protection?

𝐂𝐨𝐥𝐥𝐚𝐛𝐨𝐫𝐚𝐭𝐢𝐨𝐧 𝐚𝐧𝐝 𝐂𝐮𝐥𝐭𝐮𝐫𝐞
→ Developers blame Ops. Ops blame Dev. The release is stuck. How would you bring ownership and alignment?
→ Your team is stuck firefighting. How would you build a culture of automation and stability?

Real DevOps isn't just tools and YAML. It's owning the system end-to-end. It's being the calm in chaos. It's learning the hard way and still showing up.
