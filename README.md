# manage_user
Role ansible manage user in linux

### Thêm user trong default/main.yml
```
users:
        - huynd
        
users_info:
        - user: huynd
          fullname: "Nguyen Duc Huy"
          password: "123456"
          authorized_keys: <ssh_key>
          sudo: False

```
### Xóa user
```
users_deleted: []
```
