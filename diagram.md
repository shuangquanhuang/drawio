```mermaid
classDiagram




TemlateList --* TemplateListPage
Table --* TemlateList

TaskListTable --* TaskListPage
Table --* TaskListTable

MyTagListTable --* MyTagPage
Table --* MyTagListTable


```

### TemplateEditPage

```mermaid

TemplateEditPage *-- BasicSetting
TemplateEditPage *-- DataSetting
TemplateEditPage *-- AnnotationSetting
TemplateEditPage *-- ValidationSetting
```
