---
title: Sample Question v2A
type: select_one
shuffle_options: true
blooms: 3
correct_response: b
options:
  - id: a
    text: "`fileset("id_rsa.pub")`"
  - id: b
    text: "`file("id_rsa.pub")`"
  - id: c
    text: "`filebase64("id_rsa.pub")`"
  - id: d
  - text: "`fileexists("id_rsa.pub")`"
  - id: e
  - text: "`templatefile("id_rsa.pub")`"
---

You are developing a Terraform solution that requires the public key stored in the local file **id_rsa.pub**.

Which code should you write to output the text in **id_rsa.pub**?


---
title: Sample Question v2B
type: select_one
shuffle_options: true
blooms: 3
correct_response: b
options:
  - id: a
    text: "`fileset`"
  - id: b
    text: "`file`"
  - id: c
    text: "`filebase64`"
  - id: d
  - text: "`fileexists`"
  - id: e
  - text: "`templatefile`"
---

You are developing a Terraform solution that includes an SSH server.

Which function should you use to retrieve the public key from a local text file?



