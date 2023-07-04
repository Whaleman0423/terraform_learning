# Create Terraform Infrastructure with Docker
## Learn the Terraform workflow by deploying an NGINX Docker container

## Cloud Shell 練習環境
https://shell.cloud.google.com/cloudshell/editor?cloudshell_git_repo=https%3A%2F%2Fgithub.com%2FWhaleman0423%2Fterraform_learning.git&cloudshell_open_in_editor=Readme.md&cloudshell_workspace=001_use_terraform_build_nginx_container

## Step：
### 1. 建立 main.tf, 貼上程式碼

### 2. 初始化  
`terraform init`

terraform會在資料夾建立一些檔案，定義專案要執行哪個基礎建設
(串接 provider)

### 3. 執行, 架設環境  
`terraform apply`

列出 plan 後，輸入  
`yes`

確認  
`docker ps -a`

瀏覽網頁端口 8000，發現有 nginx 預設頁面  

### 4. 執行, 摧毀環境  
`terraform destroy`

列出 plan 後，輸入  
`yes`