# quli todo

| sDate      | eDate      | category    | title                                               | priority | status   | reason      | detail                |
| ---------- | ---------- | ----------- | --------------------------------------------------- | -------- | -------- | ----------- | --------------------- |
| 2022-09-21 |            | architect   | enable version selection to simplify architect      |          |          |             | [^simplify-architect] |
| 2022-09-15 |            | compilation | enable out path customization, for copy convenience |          |          |             |                       |
| 2022-09-09 |            | review      | compare between AOSP and af-android                 |          |          |             |                       |
| 2022-09-08 |            | compilation | fix ln out                                          |          |          |             |                       |
| 2022-09-06 |            | utility     | investigate and better end of `./build.sh`          |          |          |             | [^better-build.sh]    |
| 2022-09-05 |            | review      | odm tree structure and architect                    | .7       |          |             |                       |
| 2022-08-26 |            | solution    | flush on Ubuntu, instead of Win+Qual                | .9       |          |             |                       |
| 2022-08-26 | 2022-09-03 | instruction | ensure compile via Docker                           | -        | canceled | unnecessary | [^ins-docker-compile] |
| 2022-08-26 | 2022-09-02 | test        | check fail on eng/debug mode                        | -        | finished |             | [^test-flush-mode]    |

[^simplify-architect]:
    ![picture 1](.imgs/TODO-1663747533211-d03fe8807ec932fd4dfaa2240537d2d58ac74cf872c82a9cf9fcb5b8ecb7109f.png)  

[^better-build.sh]:
    1. it's wield with the end of `Could not find the file: "out/dist/qssi-target_files-eng.mark.zip`
    2. it's better to have this `#### build completed successfully (21:19 (mm:ss)) ####` in the end
    ![picture 1](.imgs/TODO-1662414449016-a3983ad9375fddf415ff6eef1f463d280d733483d483b1f23aa1101ae7b34886.png)  

[^ins-compile-via-docker]:
    ![picture 2](.imgs/TODO-1661499942273-e8b34641cfab7fde055290450b119b04d9eb0e67ce111b073d4022000ebfeed5.png)  

[^test-flush-mode]:
    problem:

      ![picture 1](.imgs/TODO-1661499740543-883de3c5ed77b524428b72269c0a8e9b5bfa9fbdaccf002058b1596165891ada.png)  

    result:

      ??????????????????????????? `kona-eng`  ???????????????

      ![picture 3](.imgs/TODO-1662122825672-1ff438072b04ad0d7fc1ddd35f677eab0668e94c145aefd33ba9faea03aaccb1.png)  

