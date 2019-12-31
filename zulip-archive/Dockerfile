FROM hackerkid/zulip-archive

RUN mkdir -p /zulip-archive

COPY . /zulip-archive/

CMD echo $GITHUB_WORKSPACE

ENTRYPOINT ["/zulip-archive/entrypoint.sh"]
