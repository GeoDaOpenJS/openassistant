# Type Alias: ScatterplotAdditionalData

> **ScatterplotAdditionalData**: `object`

Defined in: [packages/tools/plots/src/echarts/scatterplot/tool.ts:105](https://github.com/geodaopenjs/openassistant/blob/0a6a7e7306d75a25dc968b3117f04cb7bd613bec/packages/tools/plots/src/echarts/scatterplot/tool.ts#L105)

## Type declaration

### datasetName

> **datasetName**: `string`

### id

> **id**: `string`

### isDraggable?

> `optional` **isDraggable**: `boolean`

### isExpanded?

> `optional` **isExpanded**: `boolean`

### onSelected?

> `optional` **onSelected**: [`OnSelected`](OnSelected.md)

### regressionResults?

> `optional` **regressionResults**: `object`

#### regressionResults.regression

> **regression**: `object`

#### regressionResults.regression.intercept

> **intercept**: `object`

#### regressionResults.regression.intercept.estimate

> **estimate**: `number`

#### regressionResults.regression.intercept.pValue

> **pValue**: `number`

#### regressionResults.regression.intercept.standardError

> **standardError**: `number`

#### regressionResults.regression.intercept.tStatistic

> **tStatistic**: `number`

#### regressionResults.regression.rSquared

> **rSquared**: `number`

#### regressionResults.regression.slope

> **slope**: `object`

#### regressionResults.regression.slope.estimate

> **estimate**: `number`

#### regressionResults.regression.slope.pValue

> **pValue**: `number`

#### regressionResults.regression.slope.standardError

> **standardError**: `number`

#### regressionResults.regression.slope.tStatistic

> **tStatistic**: `number`

### showLoess?

> `optional` **showLoess**: `boolean`

### showRegressionLine?

> `optional` **showRegressionLine**: `boolean`

### theme?

> `optional` **theme**: `string`

### xData

> **xData**: `number`[]

### xVariableName

> **xVariableName**: `string`

### yData

> **yData**: `number`[]

### yVariableName

> **yVariableName**: `string`
