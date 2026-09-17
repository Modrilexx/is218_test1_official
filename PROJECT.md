# IS218 Test 1

Michael Moudatsos

A Python calculator project implementing and testing addition and subtraction.

## Setup

Create a virtual environment, activate it, and install the project requirements.

python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -r requirements.txt

## Testing

Run the student tests with pytest.

The project contains three addition tests and three subtraction tests.

python3 -m pytest
python3 -m pytest tests checks -v

## Development Notes

During development, I observed an assertion failure while testing addition. The test showed the actual returned value and the expected value, which helped identify and correct the problem.

The `.venv` directory stays local because it contains machine-specific environment files. `requirements.txt` is committed so another developer can reproduce the required dependencies.

## Issues

- Issue #1: https://github.com/Modrilexx/is218_test1_official/issues/1

- Issue #2: https://github.com/Modrilexx/is218_test1_official/issues/2

- Issue #3: https://github.com/Modrilexx/is218_test1_official/issues/3

- Issue #4: https://github.com/Modrilexx/is218_test1_official/issues/4