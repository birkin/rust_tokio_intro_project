- next:

    - <https://tokio.rs/tokio/tutorial/spawning>

        - At... """Tasks

            A Tokio task"""

---


- Notes for running mini-redis-server...

    - if redis is already running, the output will be:

            $
            $ mini-redis-server
            Error: Os { code: 48, kind: AddrInUse, message: "Address already in use" }
            $

        ...in which case: either:

        - stop redis, then try the mini-redis-server command again

        - or better, possibly, run it on a different port (6379 being the normal redis port):

                $ mini-redis-server --port 6380

---


---


