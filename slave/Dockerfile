FROM arm32v7/openjdk
COPY rootfs /

WORKDIR /
#CMD ["bash", "launch.sh"]
CMD ["java", "-DIReallyKnowWhatIAmDoingISwear", "-jar", "spigot.jar", "nogui", "--noconsole"]

EXPOSE 25565
