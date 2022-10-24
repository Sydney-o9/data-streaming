```ascii
 ______           _            ______    _                                       _                   
|_   _ `.        / |_        .' ____ \  / |_                                    (_)                  
  | | `. \ ,--. `| |-',--.   | (___ \_|`| |-'_ .--.  .---.  ,--.   _ .--..--.   __   _ .--.   .--./) 
  | |  | |`'_\ : | | `'_\ :   _.____`.  | | [ `/'`\]/ /__\\`'_\ : [ `.-. .-. | [  | [ `.-. | / /'`\; 
 _| |_.' /// | |,| |,// | |, | \____) | | |, | |    | \__.,// | |, | | | | | |  | |  | | | | \ \._// 
|______.' \'-;__/\__/\'-;__/  \______.' \__/[___]    '.__.'\'-;__/[___||__||__][___][___||__].',__`  
                                                                                            ( ( __)) 
```

## Data Streaming in Rust

Assignment 1 of Claus Matzinger's [Async Streams in Rust](https://www.manning.com/liveproject/data-streaming-with-async-rust) live project.

### Run the project

```bash
$ cargo run -- --from 2020-07-03T12:00:09Z --symbols LYFT,MSFT,AAPL,UBER,LYFT,FB,AMD,GOOG
```

### Run tests

```bash
$ cargo test
```

### Assignment

Assignment was split in 3x tasks and 3x PRs for easy review:

- [TASK-1](https://github.com/Sydney-o9/data-streaming/issues/1): Finish what was started & implement all signal calculations
     - See [PR - TASK-1](https://github.com/Sydney-o9/data-streaming/pull/2)

- [TASK-2](https://github.com/Sydney-o9/data-streaming/issues/3): Implement Async Runtime
     - See [PR - TASK-2](https://github.com/Sydney-o9/data-streaming/pull/4)

- [TASK-3](https://github.com/Sydney-o9/data-streaming/issues/5): Make Signal Calculations Async
     - See [PR - TASK-3](https://github.com/Sydney-o9/data-streaming/pull/6)

Reviewer, you can review this PR from `develop` to `master`: 
    - 👉 https://github.com/Sydney-o9/data-streaming/pull/7