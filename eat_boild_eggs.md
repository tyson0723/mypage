``````mermaid
flowchart TB
    id1[ゆで卵を食べる]
    subgraph 1
    id1
    end

    subgraph 2
    id1-->id2[卵を買う]
    id1-->id3[ゆで卵を作る]
    id1-->id4[食べる準備をする]
    end
    subgraph 3
    id2-->id5[銀行からお金をおろす]
    id5-->id6[スーパーで卵を買う]
    id3-->id7[卵を洗う]
    id7-->id8[お湯を沸かす]
    id8-->id9[卵をゆでる]
    id4-->id10[腹筋して腹を空かす]
    id10-->id11[殻を割る]
    id11-->id12[塩を振る]
    end
``````
