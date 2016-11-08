# Pemanfaatan Git secara Optimal

[Git](https://git-scm.com/) adalah *Version Control System (VCS)* yang sangat populer dan bermanfaat dalam memudahkan orang untuk berkolaborasi mengerjakan dokumen-dokumen berbasis teks. Dokumen-dokumen tersebut bisa berupa kode program atau file teks sederhana seperti artikel yang Anda baca ini.

Di internet telah banyak beredar artikel tentang Git yang cukup mudah dipahami. Namun hampir semuanya dalam bahasa Inggris. Tujuan pembuatan artikel ini adalah untuk merangkum berbagai praktek pemanfaatan Git secara optimal, sehingga pembaca dapat sesegera mungkin produktif dalam berkontribusi ke dalam proyek-proyek *Open Source* di GitHub.

## Daftar Isi

1. [Teori Dasar Git](Teori-Dasar-Git.md)
    1. [Apa itu VCS?](Teori-Dasar-Git.md#apa-itu-vcs)
    2. [Repository](Teori-Dasar-Git.md#repository)
    3. [Commits](Teori-Dasar-Git.md#commits)
    4. [Working Copy, Staging Area, Local Repository](Teori-Dasar-Git.md#local-repository-git-workflow--local-repository)
        1. [Working Copy](Teori-Dasar-Git.md#working-copy)
        2. [Staging Area](Teori-Dasar-Git.md#staging-area)
        3. [Local Repository](Teori-Dasar-Git.md#local-repository)
    5. [Branching](Teori-Dasar-Git.md#branching)
    6. [References](Teori-Dasar-Git.md#references)
    7. [Checkout](Teori-Dasar-Git.md#checkout)
2. [Git Basic Operations](Git-Basic-Operations.md)
    1. [Revert](Git-Basic-Operations.md#revert)
    2. [Reset](Git-Basic-Operations.md#reset)
    3. [Merge](Git-Basic-Operations.md#merge)
        1. [Merge Commit](Git-Basic-Operations.md#merge-commit)
        2. [Fast-Forward Merge](Git-Basic-Operations.md#fast-forward-merge)
        3. [Merge Conflicts](Git-Basic-Operations.md#merge-conflicts)
    4. [Rebase](Git-Basic-Operations.md#rebase)
    5. [Stash](Git-Basic-Operations.md#stash)
3. [Collaboration in Git](Collaboration-in-Git.md)
    1. [Remote Repository vs Local Repository](Collaboration-in-Git.md#remote-repository-vs-local-repository)
    2. [Remote Branch vs Local Branch](Collaboration-in-Git.md#remote-branch-vs-local-branch)
    3. [Clone](Collaboration-in-Git.md#clone)
    4. [Fetch](Collaboration-in-Git.md#fetch)
    5. [Pull](Collaboration-in-Git.md#pull)
    6. [Push](Collaboration-in-Git.md#push)
    7. [Git Ignore](Collaboration-in-Git.md#git-ignore)
    8. [Git Exclude](Collaboration-in-Git.md#git-exclude)
4. [Git Workflows](Git-Workflows.md)
    1. [Centralized Workflow](Git-Workflows.md#centralized-workflow)
    2. [Feature Branch Workflow](Git-Workflows.md#feature-branch-workflow)
    3. [GitFlow Workflow](Git-Workflows.md#gitflow-workflow)
    4. [Forking Workflow](Git-Workflows.md#forking-workflow)
