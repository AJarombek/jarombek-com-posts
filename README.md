# jarombek-com-posts

![Maintained Label](https://img.shields.io/badge/Maintained-Yes-brightgreen?style=for-the-badge)

### Overview

HTML (JSX) files displayed as articles on `jarombek.com`.

### Article Maintenance Status

![Maintained](https://img.shields.io/badge/-Maintained-brightgreen?style=for-the-badge)
![Outdated](https://img.shields.io/badge/-Outdated-yellow?style=for-the-badge)
![Archived](https://img.shields.io/badge/-Archived-red?style=for-the-badge)

**2023**

![01/31/2023](https://img.shields.io/badge/Configuring%20GitHub%20Actions%20to%20Test%20a%20Flask%20API-Maintained-brightgreen?style=for-the-badge)

**2022**

[![12/11/2022](https://img.shields.io/badge/Key%20Takeaways%20from%20the%202022%20Databricks%20Data+AI%20Summit-Maintained-brightgreen?style=for-the-badge)](https://jarombek.com/blog/dec-11-2022-databricks-summit-takeaways)

[![11/15/2022](https://img.shields.io/badge/Building%20and%20Testing%20Go%20Code%20using%20Please%20Build%20and%20GitHub%20Actions-Maintained-brightgreen?style=for-the-badge)](https://jarombek.com/blog/nov-15-2022-go-please-github-actions)

[![09/24/2022](https://img.shields.io/badge/Understanding%20Data%20Alignment%20in%20Go-Maintained-brightgreen?style=for-the-badge)](https://jarombek.com/blog/sep-24-2022-data-alignment)

[![09/10/2022](https://img.shields.io/badge/Answering%20Questions%20about%20Goroutines-Maintained-brightgreen?style=for-the-badge)](https://jarombek.com/blog/sep-10-2022-goroutines)

[![08/28/2022](https://img.shields.io/badge/Running%20Splunk%20and%20Basic%20SPL%20Queries%20on%20Docker-Maintained-brightgreen?style=for-the-badge)](https://jarombek.com/blog/aug-28-2022-splunk-spl)

[![03/27/2022](https://img.shields.io/badge/Running%20a%20MySQL%20Database%20Client%20on%20Kubernetes-Outdated-yellow?style=for-the-badge)](https://jarombek.com/blog/mar-27-2022-mysql-client-kubernetes)

[![03/12/2022](https://img.shields.io/badge/UI%20Testing%20SwiftUI%20Views-Outdated-yellow?style=for-the-badge)](https://jarombek.com/blog/mar-12-2022-swiftui-ui-testing)

[![02/28/2022](https://img.shields.io/badge/Creating%20SwiftUI%20Components%20Within%20a%20UIKit%20iOS%20Application-Outdated-yellow?style=for-the-badge)](https://jarombek.com/blog/feb-28-2022-swiftui-uikit)

[![02/18/2022](https://img.shields.io/badge/Building%20an%20API%20for%20Authentication%20with%20AWS%20Lambda%20and%20API%20Gateway-Outdated-yellow?style=for-the-badge)](https://jarombek.com/blog/feb-18-2022-auth-api)

[![02/05/2022](https://img.shields.io/badge/Building%20an%20API%20for%20Sending%20Emails%20with%20AWS%20Lambda%20and%20API%20Gateway-Outdated-yellow?style=for-the-badge)](https://jarombek.com/blog/feb-5-2022-function-api)

[![01/17/2022](https://img.shields.io/badge/Learning%20the%20Basics%20of%20Apache%20Airflow-Outdated-yellow?style=for-the-badge)](https://jarombek.com/blog/jan-17-2022-airflow)

[![01/10/2022](https://img.shields.io/badge/Testing%20a%20Flask%20API-Outdated-yellow?style=for-the-badge)](https://jarombek.com/blog/jan-10-2022-flask-api-testing)

[![01/02/2022](https://img.shields.io/badge/Restricting%20Access%20to%20Static%20Website%20Amazon%20S3%20Buckets%20using%20Terraform-Outdated-yellow?style=for-the-badge)](https://jarombek.com/blog/jan-2-2022-s3-restrict-access)

### Commands

**Tokenize an HTML/JSX file as JSON (MacOS)**

```bash
# Perform these commands from inside the html-tokenizer repository
cd ~/<repos-root>/html-tokenizer

# One time setup
nvm use v10.15.3
npm install -g

tokenize ../jarombek-com-posts/<year>/<filename>.html -o parsed.json
```
