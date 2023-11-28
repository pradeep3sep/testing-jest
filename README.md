# testing-jest

==> The describe function can group different tests together
==> We have to follow AAA principle ie Arrange, Act and Assert
  Arrange is in which we make all constant and act is the functiona use and the assert is the decision making thing

  eg describe('Utils test suite', () => {

        it('should return uppercase of valid string', () => {
            // arrange:
            const sut = toUpperCase;
            const expected = 'ABC'

            // act:
            const actual = sut('abc');

            // assert:
            expect(actual).toBe(expected);
        })
    
    });


  ===> Jest Matchers are the functions that assists us at comparing actual and expected objects. eg  expect(actual).toBe(expected);
