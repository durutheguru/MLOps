FROM gcr.io/deeplearning-platform-release/tf2-cpu.2-6
WORKDIR /

COPY trainer /trainer

ENTRYPOINT ["python", "-m", "trainer.train"]
