test_aco_benchmark = executable('test_aco_benchmark', 'test_aco_benchmark.c',
  dependencies: libaco_dep
)

test_aco_synopsis = executable('test_aco_synopsis', 'test_aco_synopsis.c',
  dependencies: libaco_dep
)

test_aco_tutorial_0 = executable('test_aco_tutorial_0', 'test_aco_tutorial_0.c',
  dependencies: libaco_dep
)

test_aco_tutorial_1 = executable('test_aco_tutorial_1', 'test_aco_tutorial_1.c',
  dependencies: libaco_dep
)

test_aco_tutorial_2 = executable('test_aco_tutorial_2', 'test_aco_tutorial_2.c',
  dependencies: libaco_dep
)

test_aco_tutorial_3 = executable('test_aco_tutorial_3', 'test_aco_tutorial_3.c',
  dependencies: libaco_dep
)

test_aco_tutorial_4 = executable('test_aco_tutorial_4', 'test_aco_tutorial_4.c',
  dependencies: libaco_dep,
)

test_aco_tutorial_5 = executable('test_aco_tutorial_5', 'test_aco_tutorial_5.c',
  dependencies: libaco_dep,
)

test_aco_tutorial_6 = executable('test_aco_tutorial_6', 'test_aco_tutorial_6.c',
  dependencies: libaco_dep
)

benchmark('Benchmark', test_aco_benchmark, verbose: true)
test('Synopsis', test_aco_synopsis, verbose: true)
test('Tutorial 0', test_aco_tutorial_0, verbose: true)
test('Tutorial 1', test_aco_tutorial_1, verbose: true)
test('Tutorial 2', test_aco_tutorial_2, verbose: true)
test('Tutorial 3', test_aco_tutorial_3, verbose: true)
test('Tutorial 4', test_aco_tutorial_4, verbose: true, should_fail: true)
test('Tutorial 5', test_aco_tutorial_5, verbose: true, should_fail: true)
test('Tutorial 6', test_aco_tutorial_6, verbose: true)
