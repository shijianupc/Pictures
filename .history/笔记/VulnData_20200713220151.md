# VulnData papers

## 1. Vulnerability databases
* NVD
* OSVDB(closed) / VulnDB(commercial)
* WhiteSource
* Advisories (profect)
* Issue tracker (project)
* Vulncode-db (relevant files and patches)
* Exploit-DB 
* SecurityFocus
* Mail List

## 2. Mind your own business: A longitudinal study of threats and vulnerabilities in enterprises
  * 目的：分析企业中威胁和漏洞状况
  * 方法和结果：
    * 数据：
      * File reputation logs: 文件声誉评分，由文件特征、动态行为、流行程度、下载源和签名信息计算得出。用于区分恶意文件。
      * File appearance logs: 安装在企业主机中的可执行文件，是File reputation logs的子集。
      * Enterprise classification: 描述企业特征
      * VirusTotal: 反病毒引擎检测结果
      * NVD: 漏洞影响的软件和版本
      * Internet scans: 发现server上的应用和版本
      * IP and domiain blacklists
      * Enterprise-to-IP mapping: 映射企业和IP
    ![EnterpriseThreatData]()

    * 威胁格局分析
      * 分类恶意的文件和PUP（有害程序）。
      * 分析主机和企业遇到的恶意软件和有害程序：41%的主机和97%的企业存在一个或以上这样的软件；电子设备企业中最多76.4%。
      * 纵向分析：以月为时间间隔。
      ![EnterpriseThreatFig1]()
      * 将企业IP和黑名单结合分析其恶意行为，最多的是垃圾邮件。

    * 漏洞修复行为分析
      * 客户端程序漏洞修复时间：根据File appearancre log，分析软件漏洞版本-无漏洞版本的时间间隔。
      * 服务端程序漏洞修复时间：根据Internet scans，分析漏洞修复时间

    
