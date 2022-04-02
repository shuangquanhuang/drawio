https://codesandbox.io/s/connect-context-3q1rrf?file=/src/Component.js



```mermaid
classDiagram




TemlateList --* TemplateListPage
Table --* TemlateList

TaskListTable --* TaskListPage
Table --* TaskListTable

MyTagListTable --* MyTagPage
Table --* MyTagListTable


TemplateEditPage *-- BasicSetting
TemplateEditPage *-- DataSetting
TemplateEditPage *-- AnnotationSetting
TemplateEditPage *-- ValidationSetting


```

