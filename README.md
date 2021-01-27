- next:

    -   make sure gitignore is set up to ignore the target dir

    -   <https://tokio.rs/tokio/tutorial/hello-tokio>

        - At: "Breaking it down"

---

- starting from: <https://tokio.rs/tokio/tutorial>

- try to run mini-redis-server

    - if redis is already running, the output will be:

            $
            $ mini-redis-server
            Error: Os { code: 48, kind: AddrInUse, message: "Address already in use" }
            $

            ...in which case: stop redis, then try the mini-redis-server command again

---


