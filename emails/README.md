# Cloudforet Receiving only email service

Cloudforet supports receiving only email services for contributors who want to receive emails only.

## How to use

1. Make an PR to the `cloudforet/tsc` repository.

2. File : emails/mailing.txt

* first item : cloudforet email address
* second item : forwarding email address
* Support multiple forwarding email addresses by adding more email addresses.

```
format:
cloudforet email address,forwarding email address
```

## Example 1

> Create choonho.son@cloudforet.io then forwarding to choonho.son@gmail.com

```
choonho.son@cloudforet.io,choonho.son@gmail.com
```

## Example 2

> Create choonho.son@cloudforet.io then forwarding to multiple destination (choonho.son@gmail.com and choonho.son@snu.ac.kr)

```
choonho.son@cloudforet.io,choonho.son@gmail.com,choonho.son@snu.ac.kr
```
