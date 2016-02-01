#Git is a version control system.And it is free.
Now I'm using it and learning it.

The 2th testing.

The 3th testing.

    dispatch_queue_t queue = dispatch_get_global_queue(DISPATCH_QUEUE_PRIORITY_DEFAULT, 0);
        size_t count = 10;
        dispatch_apply(count, queue, ^(size_t i) {
            NSLog(@"循环执行第%li次",i);
            //[self loadImageSource:imgUrl1];
        });
