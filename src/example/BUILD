scala_sources(
    sources=['**/*.scala'],
    dependencies = [
        "3rdparty/jvm/org/typelevel:cats-effect"
    ]
)

deploy_jar(
    name="bin",
    main="example.Main",
    dependencies=[
        ":example"
    ]
)