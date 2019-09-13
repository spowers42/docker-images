FROM deepchemio/deepchem:latest

RUN pip install jupyter

WORKDIR deepchem/examples
ENTRYPOINT ["jupyter", "notebook", "--ip 0.0.0.0", "--no-browser", "--allow-root"] 
