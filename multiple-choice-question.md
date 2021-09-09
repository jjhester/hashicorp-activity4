---
title: Sample Question v2A
type: select_one
shuffle_options: true
blooms: 2
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

Which code should you write to output the public key as a string?


---
title: Sample Question v2B
type: select_one
shuffle_options: false
blooms: 2
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
  - id: f
  - text: "None of the above"
  - id: g
  - text: "All of the above"
---

You are developing a Terraform solution that includes a secure shell (SSH) server.

Which function should you use to retrieve the public key from a local text file?



