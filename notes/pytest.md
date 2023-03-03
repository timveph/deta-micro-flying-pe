## Notes on pytest

pytest -v -m detaspace

-v: lists the tests
-m: able to run with marker (i.e. detabaes) --- a way to control which tests to run
    Just add @pytest.mark.detaspace above a function
    Also add the markers property to the pytest.ini file

Source:
- https://towardsdatascience.com/pytest-with-marking-mocking-and-fixtures-in-10-minutes-678d7ccd2f70
- https://eokulik.com/build-test-suite-with-pytest