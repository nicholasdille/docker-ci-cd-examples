# syntax=docker/dockerfile:1.0.0-experimental

FROM alpine

RUN --mount=type=secret,id=mysite.key df && ls -l /run/secrets && cat /run/secrets/mysite.key
