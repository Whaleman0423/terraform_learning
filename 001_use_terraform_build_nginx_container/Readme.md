# Create Terraform Infrastructure with Docker
## Learn the Terraform workflow by deploying an NGINX Docker container

## Step
### 建立 main.tf, 貼上程式碼

### 執行  
`terraform init`

terraform會在資料夾建立一些檔案，定義專案要執行哪個基礎建設
(串接 provider)

### 執行, 架設環境  
`terraform apply`

列出 plan 後，輸入  
`yes`

確認  
`docker ps -a`

瀏覽網頁端口 8000，發現有 nginx 預設頁面  

### 執行, 摧毀環境  
`terraform destroy`

列出 plan 後，輸入  
`yes`