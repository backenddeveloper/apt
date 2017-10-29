# apt
A ultra simple repo manager for stretch

The directory layout for the repo. (Driven by Apache2)
```
/
├── usr
│   └── bin
│       ├── repomanager
│       └── add-to-repo
│
└── var
    └── www
        └── debian
            └── dists
                └── stretch
                    └── local|main
                        └── binary-amd64
                            ├── [package1]
                            └── [package2]
```
