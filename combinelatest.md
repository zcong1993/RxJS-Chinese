###combineLatest

语法：
```
public static combineLatest(observable1: Observable, observable2: Observable, project: function, scheduler: Scheduler): Observable
```

功能:
组合多个Observable产生一个新的Observable，其发射的值根据其每个输入Observable的最新值计算。