<center> <h1>DevOps-Engineer-onboarding</h1> </center>

## Guiding thoughts
This roadmap is set up to train a DevOps engineer. In 90 days, you can learn the most necessary topics and learn the tools used by DevOps. It is designed for you to spend 2-3 hours of your daily time learning. Of course, you can complete the course in less than 90 days, but here, first of all, it is important how much you understood after completing the training. <br />
### Take time to learn.
 Don't get sucked into the minutia of decision-making or project involvement too early - there will be plenty of time for that later. In your first 30 days, try to focus on getting comfortable and **learning how things work**. Try to learn Linux basic, bash scripts, git and etc.

### Invest in relationships.
 By day 60, you'll be in **execution mode**. In your first two months, spend as much time as you can getting to know people and forming relationships. And, of course, try to learn DevOps usefull and necessary tools, such as: saltstack, monitoring tools and network basics.

### 90-day milestones
After that, you need to get some experience with sql db sush as postgresql and mysql, with Docker and Kubernetes basic, and  to completion, learn Terraform. I've put together this onboarding plan to help you get up to speed in your new role as a DevOps Engineer on DevOps team. 

**Don't be afraid to ask.** No one expects you to know how things at Area0 work right away. Take advantage of that and ask for help when you need it. Feel free to reach out if you have any questions. <br />
[@Andrey Gerasimov](https://github.com/geri4)<br />
[@Timur Nasridinov](https://github.com/timur-ND)
<br />
![alt text](https://img.medscape.com/thumbnail_library/dt_170517_dawn_sunrise_800x600.jpg)
<center> <h1>Plan</h1> </center> 

| Outcome | Steps | Tasks | Info |
| :---: | --- | --- | :---: |
|I understand how to work with **Linux**|[1. Online Linux basics course](https://stepik.org/course/73/syllabus) <br /> [2. Read about cron](https://tproger.ru/translations/guide-to-cron-jobs/) <br /> [3. Read about Linux Directory Structure](https://eng.libretexts.org/Bookshelves/Computer_Science/Operating_Systems/Linux_-_The_Penguin_Marches_On_(McClanahan)/04%3A_Managing_Linux_Storage/5.12%3A_Linux_Directory_Structure/5.12.01%3A_Linux_Directory_Structure_-_Hierarchy) |[A. Install Ubuntu on your desktop](https://ubuntu.com/download/desktop) <br /> B. Investigate your system - install **htop** and find out your resources. <br /> C. Create your own folder for your files, install usefull programms (Web-browser, Visual Studio Code, some messengers, Guake Terminal and etc.) <br /> D. Configure you workplace (configure terminal, create new patition on disk (optional) and etc.) | This steps are most necessary for begining. This can take 2-3 weeks for study. 
|I can write on **Bash**|[1. Bash tutorial](https://omgubuntu.ru/osnovy-bash-dlia-novichkov/) <br /> [2. Bash usefull commands](https://github.com/Idnan/bash-guide)<br />[3. Bash Guide full](https://tldp.org/LDP/Bash-Beginners-Guide/html/index.html)<br />[4. Effective shell](https://effective-shell.com/)| A. Try to create Bash script with basic commands (write file to disk, read file, calculate something and etc.) <br /> | This step aims to study most usefull bash commands. You can learn it in a few days.
|I know how to deal with **Git**|[1. Git Begin](https://githowto.com/ru) <br /> [2. Git 30 minutes](https://proglib.io/p/git-for-half-an-hour) <br />[3. Katacoda Git course](https://katacoda.com/courses/git)| A. Create your own repo in Github.com and try to push some files (for example, your Bash scripts from previous step) <br /> B. Clone some public repos and investigate it structure.| Git will give you version control, which will help you avoid data loss. The study will take a couple of days.
|I know what is **SSH**|[1. SSH Guide](https://www.digitalocean.com/community/tutorials/how-to-use-ssh-to-connect-to-a-remote-server-ru)<br /> [2. Add ssh key to github](https://docs.github.com/en/enterprise-server@3.0/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)| A. Generate ssh keys, add it to your github/gitlab account. <br /> B. Try to login to some server with ssh (you can ask access from [@Andrey Gerasimov](https://github.com/geri4) or [@Timur Nasridinov](https://github.com/timur-ND) or create own VMs).| Via SSH you can login to some servers, whick could be located in the other country. Very usefull tool. You will learn about it in 1 day.
|I know what is Regex|[1. Bash Regex](https://habr.com/ru/company/ruvds/blog/327896/)| A. Try to use regex in your bash scripts, for example, find some lines in file. | This is an extension of bash course. You will learn it in 1 day.
I know Network Basics|[1. Network Basic course](https://stepik.org/course/58678/)| A. Study the course, labs and practics can be skipped.| This can help you to know how network works. This can take about 1 week.
|I know what is **SaltStack**, **yaml** and **jinja** template|[1. Saltstack for 10 minutes](https://habr.com/ru/post/315012/)<br />[2. Yaml tutorial ](https://tproger.ru/translations/yaml-za-5-minut-sintaksis-i-osnovnye-vozmozhnosti/)<br /> [3. Understanding Jinja](https://docs.saltproject.io/en/latest/topics/jinja/index.html)| A. Clone https://github.com/area0dev/salt and investigate it.<br /> | Time to know about IaaC (infrastructure as a code). Saltstack give your control for files located on servers. This can take a lot of time, about 1-2 week and more.
|I know what is **Prometheus**|[1. Prometheus Guide](https://habr.com/ru/company/southbridge/blog/455290/)<br /> [2. Prometheus querying](https://prometheus.io/docs/prometheus/latest/querying/operators/)| A. Investigate https://prometheus.area0.ru/graph and try to create some queries. | Prometheus is the main devops tool for monitoring your servers and applications. You will learn about it for 1 week.
|I know how to configure **CI/CD** pipelines| [1. Read about Gitlab CI/CD](https://docs.gitlab.com/ee/ci/)<br /> [2. Read about Github Actions](https://docs.github.com/en/actions/learn-github-actions)<br />[3. Github Actions Examples](https://www.actionsbyexample.com/)<br /> [4. Read about Drone CI/CD](https://docs.drone.io/)| A. [Register in gitlab.com.](https://about.gitlab.com/free-trial/) and create repo. <br />B. Setup and register your [specific runner](https://docs.gitlab.com/runner/register/).<br /> C. Write your own gitlab-ci.yml and try build docker image. <br /> D. Try repeat this with Github Actions and Drone-CI. | CI/CD will let you become a real devops engineer:) This step can take about couple of days. 
|I know how to configure **iptables**|[1. Iptables guide](https://losst.ru/nastrojka-iptables-dlya-chajnikov) <br />[2. Iptables Full guide](https://www.opennet.ru/docs/RUS/iptables/) | A. Try to open some ports to get access from remote to your app (need nginx and virtual machine) | With iptables you can configure security on server or to your application. This take couple of days.
|I know how to use **dig** and **nslookup**| [1. Dig Manual](https://jvns.ca/blog/2021/12/04/how-to-use-dig/)<br />[2. Nslookup Manual](https://help.reg.ru/hc/ru/articles/4408047799825-%D0%A7%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-NSLOOKUP-%D0%B8-%D0%BA%D0%B0%D0%BA-%D0%B5%D0%B9-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D1%8C%D1%81%D1%8F) | A. Try to use this commands for find A and CNAME records for some domains. | This tools can find out ip of domain and troubleshoot some issues (certificate expired of something). This can take 1 day.
|I know how what is **HTTP** and **HTTPS**| [1. HTTP review](https://developer.mozilla.org/ru/docs/Web/HTTP/Overview)<br />[2. HTTPS - how it works](https://firstssl.ru/faq/general-questions/chto-takoe-https)<br />[3. HTTP VS HTTPS](https://sweb.ru/journal/article/v-chem-razlichiya-mezhdu-http-i-https/) | A. Use **curl** to some url and find out http headers. <br /> B. Try to connect to some web-sites with http and https. Answer the question: Why sometimes http redirects to https? | http/https very important protocols. Know about it will help you in network. This can take couple of days. 
|I know how to configure **Nginx**|[1. Install and Configure Nginx](https://serveradmin.ru/ustanovka-i-nastrojka-nginx/)<br />[2. Nginx beginners guide](http://nginx.org/ru/docs/beginners_guide.html)| A. Try to test your nginx config on some virtual machines. | Nginx is a web-server, which can configure access to your application on server. This can take a lot of time, about 2 weeks.
|I know how to work with **PostgreSQL**|[1. Beginners guide](https://knowledgepill.it/posts/postgresql-basics-guide/)<br />[2. Postgres course DBA1](https://youtu.be/mXA861YV7Us?list=PLaFqU3KCWw6JhHBp07QSu9uE8zahhKnTn)<br />[3. Postgres course DBA2](https://www.youtube.com/playlist?list=PLaFqU3KCWw6KycrRthIC6mESoLLQen1k6)|A. Write instructions and commands from videos in a notebook  <br /> B. Install locally PostgreSQL or MySQL and try execute some commands from DBA course. | PostgresSQL or MySQL is a databases, which are used in a lot of production in all the world. You need to know how it works and to work in it). This can take about 2 weeks.
|I know about **Docker**|[1. Video about docker](https://youtu.be/I18TNwZ2Nqg)<br />[2. Stepik docker course](https://stepik.org/course/74010/promo)  <br /> [3. Katacoda docker course](https://katacoda.com/courses/docker)| A. Create account in hub.docker.com <br /> B. Pull some images, like busybox or alpine, on your local machine and investigate it. <br /> C. Create Dockerfile and try to write your own image. Build image, run it on your desktop and push image to your repo in hub.docker.com. | Docker is powerfull tool for build and run your application. You must know it. Course can take about 2-3 weeks.
|I'm familiar with **Kubernetes**|[1. Katacoda Kubernetes course](https://katacoda.com/courses/kubernetes)<br /> [2. Helm Tutorial](https://helm.sh/docs/chart_template_guide/getting_started/) <br /> [3. Kubernetes Admin course](https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/) | A. Try to setup k8s to local machine with **minikube** or better with **Kubeadm**. <br /> B. [Deploy some pods](https://kubernetes.io/docs/concepts/workloads/pods/) to different namespaces. <br /> C. Write Helm chart and try deploy it. | Kubernetes now is most popular tool to deploy and hosts application. This is difficult system, but in the beginning, you must know some of the basics. This can take about 1 month.
|I'm familiar with **Terraform**|[1. Terraform Basic course](https://learn.hashicorp.com/terraform)| A. Try to write .tf files. | Terraform it is a IaaC tool, where you can describe your infrastrucute in file. At the beginning this take about 1 week.

## Conclusion
Of course, this plan will not teach you completely about devops, but it allows you to get the necessary knowledge base in a short time, with which further study of DevOps will become easier and more interesting.
