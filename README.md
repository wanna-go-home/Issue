# Issue 관리를 위한 Repo

## Ground Rule

1. 작업은 해당 Repo에 Issue로 등록함으로써 관리한다 
    - 작업 구분은 Android, iOS, Server 등으로 구분하며, 해당 Lavel을 Issue에 추가하여 구분한다
    - 작업 구분은 기본적으로 하나이지만, 여러 구분에서 동시에 작업이 이뤄져야 하는 경우, 각 구분들에 해당하는 Lavel을 모두 Issue에 추가하여 관리한다
    - 작업은 각 작업의 담당자를 Assignee에 추가한다. 담당자는 할일에 따라 여럿이 될 수 있다
  
 2. 작업의 시퀀스는 다음과 같다
    - 최초로 만들어진 작업 Issue는 To Do에 존재하게 된다. 이후 적절한 Mile Stone을 등록한다
    - 작업을 진행하는 경우 In Progress로 해당 작업 Issue를 변경하고 진행한다
    - 작업이 완료되어 리뷰가 필요한 경우, PR의 description에 해당 작업이슈를 다음과 같은 키워드를 사용해서 링킹한다
      
      ```
      close, closes, closed, fix, fixes, fixed, resolve, resolves, resolved
      ```
      
    - 이후 PR이 Merge되면 작업 Issue는 자동으로 Done으로 옮겨진다
    
3. Mile Stone은 2주단위 
