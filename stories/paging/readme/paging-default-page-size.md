```js
import React from "react";

import Table from "@edgesyntax/react-table";
import data from "./table.mock.json";

const Default = () => {
  return (
    <Table
      data={data}
      defaultPageSize={50} />
  )
}

export default Default;
```
