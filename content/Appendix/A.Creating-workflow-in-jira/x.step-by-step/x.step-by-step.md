### Step-by-step instructions


**Creating RISK workflow**

as seen here http://blog.diniscruz.com/2016/03/updated-jira-risk-workflow-now-with.html

7) Go to JIRA Administration , Issues

{width=50%}
![](images/b55a56ee-3dcb-11e6-941d-c6f6b6ab9dc9.png)

8) Add an issue type

{width=50%}
![](images/f35b0678-3dcb-11e6-92c5-9e7d1cf78d16.png)

9) call it Risk

{width=50%}
![](images/10a5c61e-3dcc-11e6-88fc-d87a77f5ef0e.png)

10) Go to Issue type schemes and click on 'Add Issue Type Scheme'

{width=50%}
![](images/6377d62a-3dcc-11e6-99e5-5483017ee580.png)

11) Call it Risk Scheme and add the Risk Issue type into to (click Save to continue)

{width=50%}
![](images/a87773a2-3dcc-11e6-9c7d-1688d84b3ecf.png)

12) Associate that Risk Scheme

{width=50%}
![](images/e522266c-3dcc-11e6-9aca-0f74d539b78c.png)

13) To the 'RISK - AppSec' project

{width=50%}
![](images/ecf41f8a-3dcc-11e6-8531-93c371463acd.png)

{width=50%}
![](images/1ae147f6-3dcd-11e6-9ff0-47cfdcf069ce.png)

14) Go to Workflows and add new one

{width=50%}
![](images/7816a2ae-3dcd-11e6-9a29-3b6b0f7e5c0a.png)

15) call it 'Risk Workflow'

{width=50%}
![](images/8b7a21e0-3dcd-11e6-8dfe-d2dc54af6441.png)

{width=50%}
![](images/a06fa9bc-3dcd-11e6-82e9-a42cb425f162.png)

16) Add status 'In Progress

{width=50%}
![](images/dd575028-3dcd-11e6-8b0a-c83b8966d5ea.png)

{width=50%}
![](images/fb52ee16-3dcd-11e6-850c-7dbe99753a4c.png)

17 ) Create transition from Open to In Progress

{width=50%}
![](images/5acfc2e2-3dce-11e6-88a5-f7dd104edea8.png)

{width=50%}
![](images/8d566ed2-3dce-11e6-80d1-f7526e43dd67.png)

18) Create a new Status called 'Allocated for Fix'

{width=50%}
![](images/b447ada8-3dce-11e6-887e-0ebb216149ce.png)

{width=50%}
![](images/cc65c53c-3dce-11e6-8b8e-8573d0746824.png)

19) add a transition to 'Allocated for Fix' state

{width=50%}
![](images/07e7f288-3dcf-11e6-82b2-96487b78e130.png)

20) how workflow looks like at the moment

{width=50%}
![](images/6a8619b0-3dcf-11e6-8e04-22a36ceea5b9.png)

21) Add status: Fixing, Test Fix and Fixed

with fixed set to the 'Done' Category

{width=50%}
![](images/9cfe0c30-3dd0-11e6-9b93-8df66d82e0c9.png)

21) add transitions to those status

{width=50%}
![](images/d7602a48-3dd0-11e6-990b-890168824ebd.png)

22) Add Status: Closed, 'Awaiting Risk Acceptance' , 'Risk Accepted', 'Risk Approved', 'Risk Not Approved', 'Risk Approval Expired'

{width=50%}
![](images/be8a59e8-3dd1-11e6-8075-46ce6c5e252c.png)

{width=50%}
![](images/cc8ef602-3dd1-11e6-8b15-ec88e5a83c5c.png)

{width=50%}
![](images/d5031a2a-3dd1-11e6-9188-aec6a472968d.png)

23) Add transitions (including a couple to reverse some of the steps)

{width=50%}
![](images/a1feba3e-3dd2-11e6-8a5b-28a8224b4d7d.png)

24) Completed workflow should look like this

{width=50%}
![](images/93fc50bc-3dd3-11e6-8646-ae20cc8262b3.png)

25) go to Workflow Scheme and chose to 'Add workflow scheme'

{width=50%}
![](images/d8408fd0-3dd4-11e6-9f1f-d57ce4a11ed8.png)

{width=50%}
![](images/e0dc43aa-3dd4-11e6-841e-61e8e9b0d485.png)

26) Add Existing Workflow

{width=50%}
![](images/02d9969c-3dd5-11e6-8d03-c1bcc9f1aef2.png)

{width=50%}
![](images/0b94ab8c-3dd5-11e6-9255-edb93334f424.png)

27) Assign Risk Issue type to it

{width=50%}
![](images/189871ce-3dd5-11e6-8297-92e037054900.png)

{width=50%}
![](images/2279cc92-3dd5-11e6-8ab3-9cd0a7092e2d.png)

28) exit admin and go to the RISK project's settings

{width=50%}
![](images/8f986b30-3dd5-11e6-8101-58807a9cc582.png)

29) in the Workflow page chose to Switch Scheme

{width=50%}
![](images/b6b3138c-3dd5-11e6-85a5-e5d4d3822d22.png)

30) Pick the 'Risk Workflow Scheme'

{width=50%}
![](images/d1a36520-3dd5-11e6-8630-a0cfa9ed1c9e.png)

{width=50%}
![](images/e232415e-3dd5-11e6-93f0-8ab67da3de18.png)

{width=50%}
![](images/e6d89302-3dd5-11e6-9f97-56850cb52c99.png)

{width=50%}
![](images/f3c14f5a-3dd5-11e6-8568-0ec71265df26.png)

{width=50%}
![](images/fdf2155e-3dd5-11e6-91bc-b9643324e9bd.png)

31) Test workflow (fixing path)

{width=50%}
![](images/290ef1ee-3dd6-11e6-83c3-de50cf0045d0.png)

{width=50%}
![](images/3953bbc0-3dd6-11e6-8574-95bad360819c.png)

{width=50%}
![](images/4d64417a-3dd6-11e6-91ab-0fb4f102f771.png)

{width=50%}
![](images/566f75e6-3dd6-11e6-8735-4c6fdd36fb01.png)

{width=50%}
![](images/6677a814-3dd6-11e6-86d8-8b4a37e3f4aa.png)

31) Test workflow (Accept Risk)

{width=50%}
![](images/ac037160-3dd6-11e6-8283-72bcf317c62d.png)

{width=50%}
![](images/b25a55e2-3dd6-11e6-94a5-06ea7a132635.png)

{width=50%}
![](images/bca1c3b4-3dd6-11e6-8670-48607c345c38.png)

{width=50%}
![](images/c2fc5198-3dd6-11e6-9b5a-03da9bfe529a.png)
