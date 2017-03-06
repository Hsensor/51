gulpSequence

gulp.task("taskA",["taskB",“taskC”,"taskD"],function(){});
"taskB" "taskC" "taskD"并行执行

gulp.task("taskA",gulpSequence(["taskB","taskC"],"taskD",["taskE","taskF"]));
gulpSequence();参数task 顺序执行 ，[]中并行执行任务,