import unittest

def fun(a, b):
    return a * b

class Testing(unittest.TestCase):
    def test_1(self):
        self.assertEqual(fun(2, 5), 10)  # Corrected function name and assertion

    def test_2(self):
        self.assertEqual(fun(5, 2), 10)  # Corrected function name and assertion

    def test_3(self):  # Renamed from 'testing1' to 'test_3' to match test naming convention
        self.assertEqual(fun(10, 10), 100)  # Corrected function name and assertion

if __name__ == '__main__':
    unittest.main()
