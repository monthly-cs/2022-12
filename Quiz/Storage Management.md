## Storage Management

이 퀴즈는 2022년 12월 24일에 @sumin-dev에 의해서 작성되었습니다.  
[Reference) File system](https://github.com/monthly-cs/2022-12/blob/main/Storage%20Management/1.%20File%20system.md)



#### Q. 리눅스의 `sumin.text` 파일 접근 권한을 아래의 조건에 맞게 올바르게 변경한 것은?
```
변경 전)
- 소유자: 읽기
- 그룹: 읽기
- 그 외 모두: 읽기

변경 후)
- 소유자: 읽기/쓰기/실행
- 그룹: 읽기/실행
- 그 외 모두: 실행
```

- [ ] `chmod u+wx, g+x, o+x sumin.text`
- [ ] `chmod 762 sumin.text`
- [ ] `chmod u=rwx, g+x, o-r sumin.text`
- [ ] `chmod 751 sumin.text`


