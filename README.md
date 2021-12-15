# manage_user
Role ansible manage user in linux

### Thêm user trong default/main.yml
```
users:
        - huynd
        - pdhung
        - ttlanh
        - ntchi
        
users_info:
        - user: huynd
          fullname: "Nguyen Duc Huy"
          password: "abc@123aA@"
          authorized_keys: ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDzhqne77zrwVQC7pcscxhqja7owxlKSTIuuv4m3JGBo7Tf5XYEuAu5M6rv035LHCmKhchlXqZNbov7t9ZUElE2+Bd80paSaPy6cdyV5kihW0s4pFkAWWo9oopABJR93ydS4Zwfq92fL2b2tjpb2oAYxTNdpUsBEM09gwrbhi9O2gbU5aWSoDjG+L1GXkLWIndspt71AQ7ysz8T/eLvXJ7smqRR5GAacKSiQeFtoQxqHhEyevukJ0VzJ8sPgm16fu7i/oCRRpTUoY8SAvcqQeTY2S4o8Ff1cJ6Z7Fz2AuflwuHdu9jaU3dLiJMtwyqz2cPBuI3NnRo4737q4oTtsvY5UWvzSgYWu57DD9jjCXLepmDbOTU5YmWtHNwV30TKGd61dnndulkehOuNjCmCkBUM3kgcyqpenDWrzcEJHFt4F3opHy1juV60IonG4JB/5DFmSea0wUbmfWtqcdJFakE2hilhb1UY2kkKKvkGz5udNr0ZIF8j0RrHuV5WIqerw0E= root@huynd-MS-7817
          sudo: False

        - user: pdhung
          fullname: "Phan Duy Hung"
          password: "abc@123aA@"
          sudo: True
```
### Xóa user
```
users_deleted: []
```
