```console
$ whoami
leonardo horikian — cloud architect · SRE · DevSecOps · buenos aires, AR

$ uptime
24 years in prod, load average: oracle → huawei → aws
```

```hcl
module "leonardo" {
  source  = "github.com/leohori"
  version = "24.0.0" # years of experience, semver-compliant

  role     = "Tech Lead · Senior Cloud Solutions Architect · SRE · DevSecOps"
  location = "ar-buenos-aires-1"

  previously = ["oracle", "huawei"]
  focus      = ["landing-zones", "kubernetes", "iac", "zero-trust", "compliance-as-code", "finops"]

  certifications = {
    aws        = "Solutions Architect – Associate"
    hashicorp  = "Terraform Associate"
    cncf       = "CKAD"
    huawei     = "HCIP Cloud Service Solutions Architect"
    sap        = "OS/DB Migration for SAP NetWeaver 7.30"
    oracle     = "x7 (Exadata, Exalogic, DBA, PL/SQL, …)"
  }

  lifecycle {
    prevent_destroy = true
  }
}
```

### `terraform plan` — what I'm building now

- Multi-account AWS orgs with Terragrunt, SCPs/RCPs and declarative policies as guardrails
- EKS platforms with GitOps (ArgoCD), cost-aware node scheduling and observability
- Security & compliance controls as code: Security Hub, GuardDuty, CloudTrail, Config, KMS

### Stack

[![Stack](https://skillicons.dev/icons?i=aws,gcp,kubernetes,docker,terraform,ansible,linux,bash,python,githubactions,jenkins,grafana,prometheus,postgres,mysql,mongodb,kafka,nginx&perline=10)](https://skillicons.dev)

### Writing

Old-school Oracle internals blog (in Spanish, 2007–2010) — optimizer, parsing, indexing:

- [Hard Parse, Soft Parse & "Softer" Soft Parse](https://lhorikian.blogspot.com/2007/07/hard-parse-soft-parse-softer-soft-parse.html)
- [Clustering Factor](https://lhorikian.blogspot.com/2007/09/clustering-factor.html)
- [¿Tunear en base al COSTO del plan de ejecución?](https://lhorikian.blogspot.com/2008/02/tunear-en-base-al-costo-del-plan-de.html)
- [Diferencias entre COUNT(1) y COUNT(*)](https://lhorikian.blogspot.com/2009/04/diferencias-entre-count1-y-count-parte.html)
- [Encriptando columnas con TDE en tablas con millones de registros](https://lhorikian.blogspot.com/2009/05/encriptando-columnas-con-tde-en-tablas.html)

<details>
<summary>…and 40+ more</summary>

- [WHEN OTHERS THEN NULL ;](https://lhorikian.blogspot.com/2007/07/when-others-then-null.html)
- [High Water Mark (HWM)](https://lhorikian.blogspot.com/2007/07/high-water-mark-hwm.html)
- [Index-Skip Scans](https://lhorikian.blogspot.com/2007/08/index-skip-scans_30.html)
- [Deadlocks --> ORA-00060](https://lhorikian.blogspot.com/2007/09/deadlocks-ora-00060.html)
- [Foreign Keys no indexadas](https://lhorikian.blogspot.com/2007/09/foreign-keys-no-indexadas.html)
- [DB_FILE_MULTIBLOCK_READ_COUNT (MBRC)](https://lhorikian.blogspot.com/2007/10/dbfilemultiblockreadcount-mbrc.html)
- [Explain Plan Vs. Bind Variables](https://lhorikian.blogspot.com/2008/09/explain-plan-vs-bind-variables_29.html)
- [DML Error Logging](https://lhorikian.blogspot.com/2009/05/dml-error-logging.html)
- [Full archive →](https://lhorikian.blogspot.com)

</details>

### Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-lhorikian-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lhorikian)
[![Email](https://img.shields.io/badge/email-leohori%40gmail.com-333?style=flat-square&logo=gmail&logoColor=white)](mailto:leohori@gmail.com)

<sub>`# "Debugging is fun, because it begins with a mystery."`</sub>
