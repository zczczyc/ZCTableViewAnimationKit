# ZCTableViewAnimationKit

```ruby
pod 'ZCTableViewAnimationKit'
```

第一步：导入 ```#import "TableViewAnimationKitHeaders.h"```
第二步：
```
[_tbView reloadData];
[self starAnimationWithTableView:self.tbView];

//tableview动画展示方法
- (void)starAnimationWithTableView:(UITableView *)tableView {
    //参数1：动画样式    参数2：传入要刷新的tableview
    [TableViewAnimationKit showWithAnimationType:ZCTableViewAnimationTypeFall tableView:tableView];
}

```
