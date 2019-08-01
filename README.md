# cloud-error 自定义错误

```
    // use method 1
    const cloudError = new CloudError(500, '服务器内部错误', 500);

    // another method
    const e = E.INVALID_PARAM("用户名");
```