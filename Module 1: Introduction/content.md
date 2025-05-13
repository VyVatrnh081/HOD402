## ethical hacker 
- a person who acts as an attacker and evaluates the security posture of a computer network for the purpose of minimizing risk.
- a security researcher looking for vulnerabilities in products, applications, or web services is considered an ethical hacker if he or she **responsibly discloses those vulnerabilities to the vendors or owners of the targeted research**.
- use the same tools to find vulnerabilities and exploit targets as do nonethical hackers.
- the key factor in defining **ethical versus nonethical hacking** is that **the latter involves malicious intent**.
## penetration testing/ ethical hacking
- analyzing the security posture of a network’s or system’s infrastructure in an effort to identify and possibly exploit any security weaknesses found and then determine if a compromise is possible.
## threat actors
- **organized crime**: well-funded and motivated groups that will typically use any and all of the latest attack techniques.
- **hacktivists**: make a point or to further their beliefs by stealing sensitive data and then revealing it to the public for the purpose of embarrassing or financially affecting a target.
- **state-sponsored attackers**: cyber war and cyber espionage, governments use cyber attack steal information from their opponents and cause disruption.
- **insider threats**: a threat that comes from inside an organization, trick into divulging sensitive information or mistakenly clicking on links that allow attackers to gain access to their computers.
## Environment Tests
**1. network infrastructure tests**
- Goal: evaluating the security posture of the actual network infrastructure and how it is able to help defend against attacks.
  + switches, routers, firewalls
  + AAA servers: authentication _(ai đang cố gắng truy cập)_, authorization _(họ được phép làm gì)_, and accounting _(họ đã làm những gì)_
  + IPSs - Intrusion Prevention Systems: Hệ thống ngăn chặn xâm nhập trái phép.
    
**wireless Infrastructure testing**
- try to gain unthorized access
  + bypass security mechanisms (Captive Portal)
  + break encryption (WPA2/ WPA3 craking)
- test wifi range and coverage

**2. application-based tests**
- Goal: testing for security weaknesses in enterprise applications.
  + misconfigurations
  + input validation issues
  + injection issues: SQL injection, commnad injection
  + logic flaws
- testing scope:
  + web server
  + back-end database
    
**3. penetration testing in the cloud**
- the responsibility for cloud security depends on the type of cloud model _(software as a service [SaaS], platform as a service [PaaS], or infrastructure as a service [IaaS])_.
- ensure the CSP has the same layers of security _(logical, physical, and administrative)_ in on-premise system.

**shared responsibility model**: làm rõ trách nhiệm giữa nhà cung cấp CSP và khách hàng Cloud Consumer
  + CSP chịu trách nhiệm về bảo mật của “cloud”: phần cứng, cơ sở hạ tầng vật lý, mạng lưới, dịch vụ nền tảng.
  + Khách hàng chịu trách nhiệm về bảo mật “trong cloud”: dữ liệu, cấu hình, quyền truy cập, ứng dụng, hệ điều hành (trong IaaS),...
