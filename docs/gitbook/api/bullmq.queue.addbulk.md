<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [Queue](./bullmq.queue.md) &gt; [addBulk](./bullmq.queue.addbulk.md)

## Queue.addBulk() method

Adds an array of jobs to the queue.

<b>Signature:</b>

```typescript
addBulk(jobs: {
        name: NameType;
        data: DataType;
        opts?: BulkJobOptions;
    }[]): Promise<Job<DataType, DataType, NameType>[]>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  jobs | { name: NameType; data: DataType; opts?: [BulkJobOptions](./bullmq.bulkjoboptions.md)<!-- -->; }\[\] | The array of jobs to add to the queue. Each job is defined by 3 properties, 'name', 'data' and 'opts'. They follow the same signature as 'Queue.add'. |

<b>Returns:</b>

Promise&lt;[Job](./bullmq.job.md)<!-- -->&lt;DataType, DataType, NameType&gt;\[\]&gt;
