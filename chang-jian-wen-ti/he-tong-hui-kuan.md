### **1、关于合同的提醒,操作什么的情况下会收到提醒通知**

删除合同；在合同里写跟进；在合同中为负责人新增回款时，合同负责人能收到通知

在别人的客户下新增合同，客户负责人能收到通知

创建合同的时候，如果希望合同负责人的上级能收到通知，可以通过合同审批来实现。

### **2、合同可以逐级审批吗？**

合同审批支持逐级审批。多级审批中，不管是否勾选超级管理员为审批人，超级管理员都可审批合同；如果某级审批人缺失导致无法审批时（或其他异常情况），可联系超级管理员来审批此合同；如果没有任何一级的审批人，则会自动审批通过所有审批层级。

### **3、合同审批中为何设置超管能审批所有的数据？**

超级管理员可以理解为系统中的最高权限。所以在企业中 boss确定了，就是可以直接审批通过的。正常的流程是一级审批人是主管或组长，二级审批人是 经理，三级审批人是财务，超级管理员 是在 所有审批人都有事情不在的 特殊情况下来进行特批的

### **4、什么情况下关联了合同钉钉会推送消息？**

当您客户下有商机变为赢单，就是生成合同的时候，系统会自动把客户变为成交客户，这时候钉钉会有推送，如果这个客户下的其他商机变成赢单，或者再生成合同的时候，就不会有推送提醒了，因为这个客户的状态已经变为“成交”客户。只有新增的客户才有这个提示的

### **5、合同模块有合同到期提前提醒功能吗?**

有的，合同到期是提前七天提醒，只有这一次提醒。合同计划回款是提前三天提醒的。

### **6、合同详情里的未回款金额和回款明细里的未回款金额是怎么算的，一样的算法吗？**

是一样的算法。未回款金额=合同金额-已回款金额

### **7、合同回款设置了张三为固定审批人，但是收不到审批提醒，是什么原因呢？**

### 您好，确定一下张三的数据权限是什么，如果看不到这个范围的合同，即使是固定审批人也收不到提醒的。给全公司可以审批全公司的合同回款，给部门权限，就只能审批，审批人所在部门的数据

### **8、报表里面的合同回款汇总 不是按照回款日期顺序排的吗？**

这个排序是按照合同标题排序的,同一个合同的回款是挨在一起的. 您可以通过自定义报表，自己排序了。

### **9、手机端合同详情点开里面关联的产品，为什么有些没有加号，有些手机又会显示有加号？**

如果系统有开启了合同审批、回款审批的话，产品就不能再加了就不会显示加号。如果没有开启审批的话，合同详情里面就会显示加号的按钮的。

### **10、合同驳回了后合同下面的回款还有吗？数据是如何统计的呢？**

合同驳回后，回款记录还在的，但是报表汇总不统计回款的金额的；下次再通过这个合同后回款会再统计汇总的。

### **11、怎么导入合同的时候可以同时导入多个产品？**

另起一行不用填写合同数据只写产品编号，建议价格和数量。

### **12、为什么手机端工作台新增合同数和合同总单数对不上？**

手机端工作台合同总单数；PC端工作台合同数=可用范围内的员工合同数（按签约日期）统计

PC端合同列表页和报表中心合同汇总=所有员工的合同汇总

### **13、合同回款导入为什么提示系统内有重复合同？**

这个是因为回款导入是通过系统内【合同标题】和【对应客户】进行匹配导入，但是【合同标题】和【对应客户】在系统中是重复的。合同没有查重，建议将合同标题设置为不一样，或者可以将合同标题开启自动编号规则，用系统自动编号当合同标题，这样合同标题自然是不一样的了。

