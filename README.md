# ngx-datatable

Fork of the [@swimlane/ngx-datatable](https://www.npmjs.com/package/@swimlane/ngx-datatable) package.

#### Fixed issues
 - In the OnDestroy method of DataTableBodyComponent, an attempt is made to call unsubscribe on an undefined listener object.
