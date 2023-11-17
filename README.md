# Custom tool Recon and Detech Vulnerebility
1. SOURCE: Based on osmedeus
 -------------------------------------------------------------------   
2. OVERVIEW:
- Recon:  
  + Scanning subdomain
  + Classify http, dns, nonwild, wildcards
  + Collect IP range
  + Screen result 
  + Spider available path of website
  + Brute Focre hidden path 
  + ...
- Vulnerebility:
  + Nuclei and jaeles 
  + Flexible vuln in total path 
  + sqli, cmdi, pathtraversal, xss, ssti, csrf, cors, ...

--------------------------------------------------------------------
3. BUILD:
- Step1: download osmedeus with it's templates
- Step2: cd your_path_dowload/osmedeus/workflow 
- Step3: git clone https://github.com/quyenheu/My-Custom-Tool.git
- Step4: use command to run
        + basic commnad: osmedeus scan -f hackerga2101.yaml -t target
        *ADVANCED: you can create file .txt save cookie of your target and add commnad to improve power
